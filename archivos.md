---
layout: page
title: Archivos
permalink: /archivos/
---

Aquí puedes encontrar todas las entradas del blog organizadas por etiquetas y
categorías.

### Nube de etiquetas

Juegos en <span class="label label-primary">azul</span>, concursos y premios en 
<span class="label label-success">verde</span>, eventos y ferias en <span
class="label label-info">azul clarito</span>, etiquetas generales en <span
class="label label-warning">naranja</span> y cosas relacionadas con rol en
<span class="label label-danger">rojo</span>.

<p class="text-left">
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
    {% if tag[0] == "Augmented Reality" or
        tag[0] == "Dyson's Delve" or
        tag[0] == "ENnie" or 
        tag[0] == "Labyrinth Lord" or
        tag[0] == "Mothership" or 
        tag[0] == "Mothership: Dead Planet" or 
        tag[0] == "OSR" or 
        tag[0] == "One Page Dungeon" or 
        tag[0] == "Rol" or
        tag[0] == "Shinobi & Samurai" or
        tag[0] == "Strange Nations" or 
        tag[0] == "Swarp Swords & Sinister Spells" or 
        tag[0] == "The Black Isle" or
        tag[0] == "Veinscrawl" %}
        <span class="label label-danger">#<a class="tag-color"
        href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></span> 
    {% else %}
        {% if tag[0] == "9 Card Game Print & Play Design Contest" or
            tag[0] == "Golden Geek" or
            tag[0] == "Solitaire Print & Play Design Contest" %}
            <span class="label label-success">#<a class="tag-color"
            href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></span> 
        {% else %}
            {% if tag[0] == "Campaña" or tag[0] == "Expansión" or
            tag[0] == "Kickstarter" or tag[0] == "Print & Play" or
            tag[0] == "Tabletopia" or tag[0] == "Tops" or
            tag[0] == "Verkami" %}
                <span class="label label-warning">#<a class="tag-color"
                href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></span> 
            {% else %}
                {% if tag[0] == "GenCon" or tag[0] == "Essen Spiel" or
                    tag[0] == "UKGE" %}
                    <span class="label label-info">#<a class="tag-color"
                    href="/etiqueta/{{tag[0] | slugify:
                    "latin"}}">{{tag[0]}}</a></span> 
                {% else %}
                    <span class="label label-primary">#<a class="tag-color"
                    href="/etiqueta/{{tag[0] | slugify:
                    "latin"}}">{{tag[0]}}</a></span> 
                {% endif %}
            {% endif %}
        {% endif %}
   {% endif %}
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


