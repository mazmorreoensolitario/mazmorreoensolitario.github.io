---
layout: page
title: Artículos generales
permalink: /articulos-generales/
---

Aquí tienes los **artículos de carácter general relacionados con los juegos
de mesa o wargames en solitario** y que no entran en ninguna otra
categoría:

<div class="col-md-10">
{% assign sorted-posts = site.posts | where: "categories", "General" %}
{% assign sorted = sorted-posts | sort: 'date' | reverse %}
{% for post in sorted %}
        <div class="image-container">
            <a href="{{site.url}}{{post.url}}">
            <img class="crop-sidebar" src="{{post.imghtml}}">
            <div class="text-block"><h5>{{post.title | truncate: 40}}</h5>
            </div></a>
        </div>
{% endfor %}
</div>
