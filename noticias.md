---
layout: page
title: Noticias
permalink: /noticias/
---

Aquí tienes los **artículos de la sección de noticias**, y como sabes, solo nos
interesan las **noticias relacionadas con los juegos jugables en solitario**:


<div class="col-md-12">
<div class="col-md-10">
{% assign sorted-posts = site.posts | where: "categories", "Noticias" %}
{% assign sorted = sorted-posts | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% if post.general %}
        <div class="image-container">
          <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 60}}</h5></div></a>
        </div>
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
{% assign sorted-posts = site.posts | where: "categories", "Noticias" %}
{% assign sorted = sorted-posts | sort: 'date' | reverse %}
{% assign posts = sorted | where: "tags", "Boletín Informativo Solitario" %}
{% for post in posts %}
    <div class="image-container">
          <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 60}}</h5></div></a>
        </div>
{% endfor %}
</div>
</div>
