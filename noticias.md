---
layout: page
title: Noticias
permalink: /noticias/
---

Aquí tienes los **artículos de la sección de noticias**, y como sabes, solo nos
interesan las **noticias relacionadas con los juegos jugables en solitario**:


<div class="col-md-12">
<div class="col-md-10">
{% for category in site.categories %}
    {% if category[0] == "Noticias" %}
    {% assign sorted = category[1] | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% if post.general %}
        <div class="image-container">
          <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 60}}</h5></div></a>
        </div>
    {% endif %}
    {% endfor %}
    {% endif %}
{% endfor %}
</div>
</div>

<div class="col-md-12"></div>
<div class="col-md-12"></div>
<div class="col-md-12"></div>

Y no te olvides de visitar el **Boletín Informativo Solitario**, un boletín
mensual donde agrupamos todas las noticias sobre **juegos de mesa, wargames y rol
en solitario del mes:**

<div class="col-md-12">
<div class="col-md-10">
{% assign sorted = site.posts | sort: 'date' | reverse %}
{% for post in sorted %}
{% for tag in post.tags %}
{% if  tag == "Boletín Informativo Solitario" %}
    <div class="image-container">
          <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 60}}</h5></div></a>
        </div>
{% endif %}
{% endfor %}
{% endfor %}
</div>
</div>
