---
layout: page
title: Análisis y reseñas
permalink: /analisis/
---

En las **reseñas** (*narración sucinta (breve)* según la RAE) os vais a
encontrar con información específica acerca de algún aspecto de un juego.

En los **análisis** vais a poder encontrar información objetiva del juego: de
qué va, cómo se prepara una partida, cuáles son las reglas, ejemplos
de juego, además de nuestra opinión subjetiva y una pequeña puntuación en
 **Monedas de Mazmorreo**.

Las **Monedas de Mazmorreo** son un recurso que representa la inversión de
tiempo VS ganas-de-jugar/satisfacción/buen-rollismo que me aporta un
juego. Básicamente, indica si el tiempo que invertimos en un juego merece la
pena, porque nos hace vivir una experiencia buena o no.
La escala es la siguiente:

* 1 moneda  - creo que prefiero hacer otra cosa
* 2 monedas - es algo entretenido, pero no me engancha
* 3 monedas - me lo paso bien jugando a este juego
* 4 monedas - ¡este juego es genial!
* 5 monedas - ES IDEAL

El indicador **dependencia del idioma** de un juego (únicamente
en los juegos en inglés) explica cómo de importante es que tengáis soltura en
el idioma para poder jugar al juego y entenderlo. **NO significa** que un juego
tenga un "nivel de inglés alto" o "nivel de inglés bajo", eso es una
desfachatez y no es una métrica objetiva. Con esta métrica trato de explicar
cuántos elementos dependen de que entendáis el idioma; por ejemplo, si el juego
solamente tiene el manual en inglés y el resto es independiente del idioma,
entonces tendrá una dependencia *baja*, si por otro lado, además del manual el
juego requiere que estéis leyendo cartas y estas no están doblemente
codificadas con iconos, entonces la dependencia será *alta*.

## Índice por puntuaciones

<div class="col-md-12">
<h3>5 monedas</h3>
<p><strong>ES IDEAL.</strong> — Si no sabes a qué jugar, <strong>debes</strong>
empezar por estos. <strong>Son 
juegos ideales que te puedo recomendar sin ninguna duda.</strong></p>

<div class="col-md-12">
<p><i>(actualmente me encuentro en búsqueda del juego ideal, no sé aún si
existe)</i></p>
</div>
</div>

<div class="col-md-12">
<h3> 4.5 monedas</h3>
<p><strong>Fantástico.</strong>  — 
Juegos fantásticos, de los que quieres volver a jugar cuando has terminado la
partida, y si no puedes volver a jugar acto seguido, es por Una Causa
Mayor. También <strong>te los recomiendo sin dudas.</strong></p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 4.5 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<h3> 4 monedas</h3>
<div class="col-md-12">
<p><strong>¡Este juego es genial!</strong> Voy a jugar otra vez ya mismo.  — 
Juegos muy muy buenos, también quiero jugar otra vez según he terminado la
partida, pero a lo mejor no en el mismo día. <strong>Recomendados.</strong></p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 4 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<h3> 3.5 monedas</h3>
<div class="col-md-12">
<p><strong>Me lo paso muy bien jugando a este juego.</strong>  — Estos juegos me gustan, son
buenos, pero no los saco a la mesa tan a menudo porque tengo otros que me
tiran más. Yo los llamo <i>juegos estacionales</i>, a veces me dan rachas en los que
los juego mucho y otras veces pasan temporadas muy largas sin
jugarlos. <strong>Solamente los recomiendo si algún aspecto del juego te llama la
atención.</strong></p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 3.5 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<h3> 3 monedas</h3>
<div class="col-md-12">
<p><strong>Me lo paso bien jugando a este juego.</strong>  — El último escalón de los juegos que
puedo decir que me gustan. Son los que menos saco a la mesa, también son 
<i>estacionales</i> (mira qué es esto en la descripción de la categoría superior).</p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 3 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<h3> 2.5 monedas</h3>
<div class="col-md-12">
<p><strong>Es entretenido, pero no me engancha.</strong> — En estos juegos empiezo a ver algunas
pegas, y como dice el título, son entretenidos, pero no me enganchan y salvo
que se cambie algo en el juego, dudo que repita.</p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 2.5 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<h3>2 monedas</h3>
<div class="col-md-12">
<p><strong>Es algo entretenido, pero no me engancha.</strong>  — A estos juegos les veo pegas
mayores que a los de la categoría anterior y hasta me pueden llegar a parecer
aburridos.</p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 2 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>


<h3> 1.5 monedas</h3>
<div class="col-md-12">
<p><strong>Creo que prefiero hacer otra cosa.</strong>  — Como dice el título, creo
que prefiero hacer alguna otra actividad de ocio antes que jugar a estos
juegos, no conectan conmigo.</p>

<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories","Análisis" %}
{% assign sorted = sorted-posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.score and post.score == 1.5 %}
            <div class="image-container">
                <a href="{{site.url}}{{post.url}}">
                    <img class="crop-sidebar" src="{{post.imghtml}}">
                    <div class="text-block"><h5>{{post.game}}</h5></div>
                </a>
            </div>
        {% endif %}
{% endfor %}
</div>
</div>

<p></p>
<h3> 1 moneda</h3>
<div class="col-md-12">
    <p>
    <strong>Definitivamente, prefiero hacer otra cosa.</strong>  — Espero no jugar a ningún juego
    de esta categoría y darme cuenta antes de jugarlo que no es lo mio.</p>
    <p><i>(de momento no he jugado a ninguno de estos, existen, pero evito
    jugarlos)</i></p>

</div>

## Primeras impresiones

Aquí tenéis una lista de **primeras impresiones** de juegos, que eventualmente
tendrán un análisis del mismo:

<div class="col-md-12">
<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories", "Primeras impresiones" %}
{% assign sorted = sorted-posts | sort: 'game' %}
    {% for post in sorted %}
        <div class="image-container">
            <a href="{{site.url}}{{post.url}}">
                <img class="crop-sidebar" src="{{post.imghtml}}">
                <div class="text-block"><h5>{{post.game}}</h5></div>
            </a>
        </div>
    {% endfor %}
</div>
</div>
<div class="col-md-12"><h1></h1></div>

## Demos y protos

Estas son mis impresiones sobre **demos de juegos**, en muchos casos de
**versiones todavía sin terminar** de juegos que saldrán en el futuro, por lo
que no puedo hacer un análisis o primeras impresiones per se, ya que el juego
aún no está en su versión final:

<div class="col-md-12">
<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories", "Demos" %}
{% assign sorted = sorted-posts | sort: 'game' %}
    {% for post in sorted %}
        <div class="image-container">
            <a href="{{site.url}}{{post.url}}">
                <img class="crop-sidebar" src="{{post.imghtml}}">
                <div class="text-block"><h5>{{post.game}}</h5></div>
            </a>
        </div>
    {% endfor %}
</div>
</div>
<div class="col-md-12"><h1></h1></div>

## Ojeando

Aquí os presento brevemente algunos juegos:

<div class="col-md-12">
<div class="col-md-8">
{% assign sorted-posts = site.posts | where: "categories", "Ojeando" %}
{% assign sorted = sorted-posts | sort: 'game' %}
    {% for post in sorted %}
        <div class="image-container">
            <a href="{{site.url}}{{post.url}}">
                <img class="crop-sidebar" src="{{post.imghtml}}">
                <div class="text-block"><h5>{{post.game}}</h5></div>
            </a>
        </div>
    {% endfor %}
</div>
</div>
<div class="col-md-12"><h1></h1></div>

## Índice alfabético

<ul>
{% assign sorted = site.posts | sort: 'game' %}
{% for post in sorted %}
    {% if post.game %}
        <li><a href="{{ post.url }}">{{ post.title }}.</a></li>
    {% endif %}
{% endfor %}
</ul>
