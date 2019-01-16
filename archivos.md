---
layout: page
title: Archivos
permalink: /archivos/
---

Aquí puedes encontrar todas las entradas del blog organizadas por etiquetas y
categorías.

### Nube de etiquetas

<p class="text-left">
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
    <span class="label label-primary">#{{tag[0]}}</span>
{% endfor %}
</p>

### Categorías

En esta sección tienes ordenadas las entradas del blog por categoría:

{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
  <h4>{{ category[0] }}</h4>
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

