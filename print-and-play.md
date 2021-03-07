---
layout: page
title: El rincón de los Print & Play
permalink: /rincon-print-and-play/
---

![](https://live.staticflickr.com/65535/51011850093_2124f17fd2_o.jpg)

El género print 'n' play, **imprime y juega**, necesita un espacio dedicado en 
nuestro blog. Cada vez más autores eligen esta forma de darse a conocer al
mundo de los juegos de mesa para luego ser fichados por editoriales
([Mini Rogue]({{site.baseurl}}/2020/05/23/ojeando-mini-rogue/),
[Maquis]({{site.baseurl}}/2019/03/09/analisis-maquis/),
[Orchard]({{site.baseurl}}/2019/07/23/analisis-orchard/), [Pocket
Landship]({{site.baseurl}}/2019/02/09/analisis-pocket-landship/)....) y 
publicar sus juegos de forma profesional.

En este rincón analizamos los juegos que hemos imprimido y jugado.


#### Material para ediciones en print & play

Esta es una lista en progreso y no exhaustiva, de material para hacer ediciones
print & play que puedo recomendar:

* Puedes usar una *recortadora de esquinas* para hacer el acabado de tus cartas
  más profesional, yo uso la [Sunstar Kadomaru Pro](https://amzn.to/2JJjmti).

  Puede recortar 3-4 cartas a la vez y cartulina, pero no se puede usar para
  cartón.

* Antes yo cortaba las cartas con tijeras, pero me he pasado al cuchillo y
  regla, me resulta más rápido hacer todo así. Las cizallas también puede que
  sean una buena opción, pero las calidades dejan bastante que desear.
  - [Cuchillo con tres recambios APLI](https://amzn.to/38V4Gm2)
  - [Regla de acero](https://amzn.to/2UEXDFM)
  - [Base para cortar APLI](https://amzn.to/36JRDRv)


#### Índice alfabético de juegos

<div class="col-md-12">
<div class="col-md-8">
{% for category in site.categories %}
{% if category[0] == "Print & play" %}
{% assign sorted = (category[1] | sort: 'game') %}
{% for post in sorted  %}
<div class="image-container">
<a href="{{site.url}}{{post.url}}">
<img class="crop-sidebar" src="{{post.imghtml}}">
<div class="text-block"><h5>{{post.game | truncate: 40}}</h5></div></a>
</div>
{% endfor %}
{% endif %}
{% endfor %}
</div>
</div>
