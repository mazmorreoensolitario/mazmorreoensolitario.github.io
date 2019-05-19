---
layout: page
title: Estamos ojeando...
permalink: /ojeando/
---


Estos son los juegos a los que recientemente hemos echado el ojo y queremos
probar, por cada juego explicamos qué nos llama la atención, porqué creemos
que puede ser un buen juego, además de nuestras expectativas.


{% for category in site.categories %}
{% if category[0] == "Ojeando" %}
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

Esta es una lista (en orden de: "según me vaya acordando") de diversos juegos
en solitario que *igual* aparecen en algún momento en el blog:

32. Normandy '44
31. Root
30. No Retreat!
29. Spirit Island
28. Unbroken
27. Legends Untold
26. The City of Kings
25. Onirim
24. Arkham Noir
23. The Lost Expedition
22. Burgle Bros
21. Apocrypha Adventure Card Game
20. Pandemic: Fall of Rome
19. Reinos de Papel: Más allá de las puertas
18. Volfyrion
17. Dungeon Raiders
16. Discover: lands unknown
15. Agricola
14. Caverna: The Cave Farmers
13. A4 Quest
12. The Artemis Project
11. Near and Far
9. Pathfinder Adventure Card Game
8. D-Day Dice
7. Unknown
5. Vast: The Crystal Caverns
4. Escape the Dark Castle
3. Desolate
2. Tiny Epic Quest
{: reversed="reversed"}
