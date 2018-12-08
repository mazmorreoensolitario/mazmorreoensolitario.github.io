---
layout: page
title: Archivos
permalink: /archivos/
---

Aquí tienes el archivo de todo lo que hemos hablado en este blog:

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
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
    {{ post.date | date: "%Y"}}. <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
