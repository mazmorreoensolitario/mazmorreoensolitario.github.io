---
layout: page
title: Listas y tops
permalink: /listas-y-tops/
---

¿Se pueden organizar juegos de mesa, rol o wargames en una lista ordenada? ¿Son
los tops de algún evento? Aquí recojo todas los artículos de **listas y tops**.

<div class="pack">
    {% assign sorted-posts = site.posts | where: "categories", "Listas" %}
    {% assign sorted = sorted-posts | sort: 'date' | reverse %}
    {% for post in sorted %}
    <div class="col-md-4 card">
        <a href="{{ post.url | prepend: site.baseurl }}" class="index-anchor">    
            <div class="panel panel-default">
                {% if post.imghtml %}
                <img
                    class="try-to-crop" 
                    src="{{post.imghtml}}" alt="{{post.title}}">
                {% else %}
                {% if post.img %}
                <img class="try-to-crop"
                    src="{{site.baseurl}}/images/{{post.img}}"
                    alt="{{post.title}}">
                {% else %}
            <img class="try-to-crop"
                src="{{site.baseurl}}/images/logo.png"
                 alt="{{site.title}}">
            {% endif %}
            {% endif %}
            <div class="panel-body">
            <h3 class="panel-title pull-left">
              {{ post.title | truncate: 70 }}
            </h3>
            <br>
            <div clas="pull-left">
              {% assign categ_sorted = post.categories | sort %}
              <span class="label label-default">
                {{categ_sorted[0]}}
              </span>
              <span class="post-meta pull-right"><small>
                {% assign m = post.date | date: "%-m" %}
                {{ post.date | date: "%-d" }}
                {% case m %}
                {% when '1' %}Enero
                {% when '2' %}Febrero
                {% when '3' %}Marzo
                {% when '4' %}Abril
                {% when '5' %}Mayo
                {% when '6' %}Junio
                {% when '7' %}Julio
                {% when '8' %}Agosto
                {% when '9' %}Septiembre
                {% when '10' %}Octubre
                {% when '11' %}Noviembre
                {% when '12' %}Diciembre
                {% endcase %}
                {{ post.date | date: "%Y" }}
                </small>
              </span>
              <div class="pull-right">
                <span>
                  <small>
                    <a href="{{post.url | prepend: site.baseurl}}#disqus_thread">
                    </a> <i class="fa fa-comment">&nbsp;&nbsp;</i>
                  </small>
                </span>
              </div>
            </div>
          </div>
          <div class="panel-body"><small>
              {% if post.post_desc %}
              {{ post.post_desc | strip_html | strip_newlines | truncate: 180}}
              {% else %}
              {{ post.excerpt | strip_html | strip_newlines | truncate: 180 }}
              {% endif %}
            </small>
          </div>
        </div>
        </a>
      </div>
      {% endfor %} <!-- sorted posts -->
  </div> <!-- pack -->

