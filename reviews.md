---
layout: page
title: Análisis y reseñas
permalink: /analisis/
---

En nuestros **análisis** de juegos vais a encontrar una puntuación dada en
**Monedas de Mazmorreo**. Estas monedas representa la inversión de
tiempo frente a la satisfacción que aporta un juego. 

* **1 moneda** - no me gusta, definitivamente no quiero volver a jugarlo
* **1.5 monedas** - no me gusta, prefiero hacer otra cosa que jugarlo
* **2 monedas** - juego *algo* entretenido, pero no me engancha
* **2.5 monedas** - juego entretenido, pero no me engancha 
* **3 monedas** - juego bueno, me lo paso bien jugando
* **3.5 monedas** - juego *muy* bueno, me lo paso muy bien jugando
* **4 monedas** - juego genial
* **4.5 monedas** - juego fantástico
* **5 monedas** - JUEGO IDEAL

<blockquote class="rpg-comment">Si queréis convertir la escala de puntuaciones
a una sobre 10 puntos, multiplicad las puntuación en monedas por dos, la
puntuación se encontrará entre esa cifra y el siguiente entero (no
incluido). Por ejemplo, un juego de 3.5/5 monedas sería un juego de 7 a 7.99 en 
escala de 10 puntos.</blockquote>

Salta al **[Índice por puntuaciones](#índice-por-puntuaciones)**.

A las [Primeras impresiones](#primeras-impresiones), o a las [Demos y
protos](#demos-y-protos).

Nota: El indicador **dependencia del idioma** de un juego (únicamente en los
juegos en inglés) explica cómo de importante es que tengáis soltura en el
idioma para poder jugar al juego y entenderlo. Esto **no significa** que un
juego tenga un "nivel de inglés alto" o "nivel de inglés bajo", eso no es una
métrica objetiva y por tanto, no es útil.  Con la dependencia del idioma trato
de explicar cuántos elementos dependen de que entendáis el idioma para poder
jugar al juego. Por ejemplo, si el juego solamente tiene el reglamento en
inglés y el resto es independiente del idioma, entonces tendrá una dependencia
*baja*, ya que un único elemento hace de "barrera de idioma". Si por otro lado,
además del reglamento el juego requiere leer cartas y estas no están doblemente
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
<p><strong>¡Este juego es genial!</strong> Quiero jugar otra vez ya mismo.  — 
Juegos geniales, de volver a jugar una y otra vez. <strong>Muy recomendados.</strong></p>

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
<p><strong>Me lo paso muy bien jugando a este juego.</strong>  — Estos juegos
me gustan mucho, son muy buenos, pero igual no ven tanto mesa o son <i>juegos
estacionales</i>, a los que vas a jugar poco o mucho por
rachas. <strong>Recomendados.</strong></p>

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
<p><strong>Me lo paso bien jugando a este juego.</strong>  — El último escalón
de los juegos que me gustan. Son los que menos saco a la mesa, también son 
<i>estacionales</i> (mira qué es esto en la descripción de la categoría
superior). <strong>Solamente los recomiendo si algún aspecto del juego te llama
la atención.</strong></p>

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
<p><strong>Es entretenido, pero no me engancha.</strong> — En estos juegos
empiezo a ver algunas pegas, y como dice el título, son entretenidos, pero no
me enganchan y salvo que se cambie algo en el juego, dudo que repita.</p>

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
<p><strong>Es algo entretenido, pero no me engancha.</strong>  — A estos juegos
les veo pegas mayores que a los de la categoría anterior y hasta me pueden
llegar a parecer aburridos.</p>

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
