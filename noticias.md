---
layout: page
title: Noticias
permalink: /noticias/
---

Aquí tienes los **artículos de la sección de noticias**, y como sabes, solo nos
interesan las **noticias relacionadas con los juegos jugables en solitario**:


<div class="col-md-10">
{% for category in site.categories %}
    {% if category[0] == "Noticias" %}
    {% assign sorted = (category[1] | sort: 'date' | reverse) %}
    {% for post in sorted %}
        <div class="image-container">
          <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 60}}</h5></div></a>
        </div>
    {% endfor %}
    {% endif %}
{% endfor %}
</div>
