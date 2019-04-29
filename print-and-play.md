---
layout: page
title: El rincón de los Print & Play
permalink: /rincon-print-and-play/
---

El género print 'n' play, imprime y juega, necesita un espacio dedicado en
nuestro blog. En este rincón analizamos los juegos que hemos imprimido y jugado.

{% for category in site.categories %}
{% if category[0] == "Print & play" %}
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

#### Material para ediciones en print & play

Esta es una lista en progreso y no exhaustiva, de material para hacer ediciones
print & play que puedo recomendar:

* Puedes usar una *recortadora de esquinas* para hacer el acabado de tus cartas
  más profesional, yo uso la [Sunstar Kadomaru Pro](https://amzn.to/2JJjmti).

  Puede recortar 3-4 cartas a la vez y cartulina, pero no se puede usar para
  cartón.

