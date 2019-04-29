---
layout: page
title: Análisis y reseñas
permalink: /analisis/
---

En los **análisis** vais a poder encontrar información objetiva del juego: de
qué va, cómo se prepara una partida, cuáles son las reglas, ejemplos
de juego, además de nuestra opinión subjetiva y una pequeña puntuación en
 *Monedas de Mazmorreo*.

Las Monedas de Mazmorreo son un recurso que representa la inversión de
tiempo VS ganas-de-jugar/satisfacción/buen-rollismo que me aporta un
juego. Básicamente, indica si el tiempo que invertimos en un juego merece la
pena, porque nos hace vivir una experiencia buena o no.
La escala es la siguiente:

* 1 moneda  - creo que prefiero hacer otra cosa
* 2 monedas - es entretenido, pero no me engancha
* 3 monedas - me lo paso muy bien jugando a este juego
* 4 monedas - ¡este juego es genial! Voy a jugar otra vez ya mismo
* 5 monedas - ES IDEAL

**Por favor, lee abajo con más detalle qué significa para mí exactamente cada
cantidad de monedas.**

En las **reseñas** os vais a encontrar con información acerca de algunos
aspectos de un juego de los que hay que hablar a parte.

 <img width="50" src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50" src="{{site.baseurl}}/favicon.ico">

Aquí tenéis una lista de los análisis y reseñas más recientes:

{% for category in site.categories %}
{% if category[0] == "Reseña" or category[0] == "Análisis" %}
<ul>
{% for post in category[1] %}
<li>
    {% assign m = post.date | date: "%-m" %}
    {{ post.date | date: "%-d" }}
    {% case m %}
    {% when '1' %}Ene,
    {% when '2' %}Feb,
    {% when '3' %}Mar,
    {% when '4' %}Abr,
    {% when '5' %}May,
    {% when '6' %}Jun,
    {% when '7' %}Jul,
    {% when '8' %}Ago,
    {% when '9' %}Sep,
    {% when '10' %}Oct,
    {% when '11' %}Nov,
    {% when '12' %}Dic,
    {% endcase %}
    {{ post.date | date: "%Y"}}. <a href="{{ post.url }}">{{ post.title }}.</a>
</li>
{% endfor %}
</ul>
{% endif %}
{% endfor %}

 <img width="50" src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50" src="{{site.baseurl}}/favicon.ico">

Para poder localizar cuántas Monedas de Mazmorreo he dado a cada juego, además
de una descripción detallada de qué significa que un juego esté en una
categoría u otra, podéis utilizar esta lista:

### 5 monedas
**ES IDEAL.** Si no sabes a qué jugar, **debes** empezar por estos. **Son juegos
ideales que te puedo recomendar sin ninguna duda.**
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 5 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

*(actualmente me encuentro en búsqueda del juego ideal, no sé aún si existe)*

### 4.5 monedas
**¡Este juego es genial! Voy a jugar otra vez ya mismo (mitad superior).**
Juegos geniales, de los que quieres volver a jugar cuando has terminado la
partida, y si no puedes volver a jugar acto seguido, es por Una Causa
Mayor. **También te los recomiendo sin dudas.**

*(estos juegos existen, pero aún no os he hablado de ellos)*
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 4.5 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 4 monedas
**¡Este juego es genial! Voy a jugar otra vez ya mismo (mitad inferior).**
Juegos muy muy buenos, también quiero jugar otra vez según he terminado la
partida, pero a lo mejor no en el mismo día. **Recomendados.**
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 4 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 3.5 monedas
**Me lo paso muy bien jugando a este juego.** Estos juegos me gustan, son
buenos, pero no los saco a la mesa tan a menudo porque tengo otros que me
tiran más. Yo los llamo *juegos estacionales*, a veces me dan rachas en los que
los juego mucho y otras veces pasan temporadas muy largas sin
jugarlos. **Solamente los recomiendo si algún aspecto del juego te llama la
atención.**
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 3.5 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 3 monedas
**Me lo paso bien jugando a este juego.** El último escalón de los juegos que
puedo decir que me gustan. Son los que menos saco a la mesa, también son 
*estacionales* (mira qué es esto en la descripción de la categoría superior). 
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 3 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 2.5 monedas
**Es entretenido, pero no me engancha.** En estos juegos empiezo a ver algunas
pegas, y como dice el título, son entretenidos, pero no me enganchan y salvo
que se cambie algo en el juego, dudo que repita.
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 2.5 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 2 monedas
**Es algo entretenido, pero no me engancha.** A estos juegos les veo pegas
mayores que a los de la categoría anterior y hasta me pueden llegar a parecer
aburridos. 
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 2 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 1.5 monedas
**Creo que prefiero hacer otra cosa.** Como dice el título, creo que prefiero
hacer alguna otra actividad de ocio antes que jugar a estos juegos, no conectan
conmigo. 
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 1.5 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}

### 1 moneda
**Prefiero hacer otra cosa.** Espero no jugar a ningún juego de esta categoría
y darme cuenta antes de jugarlo que no es lo mio.

*(de momento no he jugado a ninguno de estos, existen, pero evito jugarlos)*
{% for category in site.categories %}
{% if category[0] == "Análisis" %}
<ul>
    {% for post in category[1] %}
        {% if post.score and post.score == 1 %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endif %}
{% endfor %}
