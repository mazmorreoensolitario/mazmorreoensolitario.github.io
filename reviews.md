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

En las **reseñas** os vais a encontrar con información acerca de algunos
aspectos de un juego de los que hay que hablar a parte.

 <img width="50" src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50"
 src="{{site.baseurl}}/favicon.ico"><img width="50" src="{{site.baseurl}}/favicon.ico">

Aquí tenéis una lista de los análisis y reseñas más recientes:

{% for category in site.categories %}
{% if category[0] == "Análisis" %}
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
