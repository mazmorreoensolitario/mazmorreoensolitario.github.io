---
layout: page
title: Archivos
permalink: /archivos/
---

Aquí puedes encontrar todas las entradas del blog organizadas por etiquetas y
categorías.

### Nube de etiquetas

<span class="label label-primary"><strong>Juegos</strong></span>,
<span class="label label-success"><strong>concursos y premios</strong></span>,
<span class="label label-info"><strong>eventos y ferias</strong></span>,
<span class="label label-warning"><strong>general</strong></span>
<span class="label label-danger"><strong>rol</strong></span>,
<span class="label label-grey"><strong>wargames</strong></span>.

<p class="text-left">
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
    {% if tag[0] == "Augmented Reality" or
        tag[0] == "Lost in the Deep" or tag[0] == "The Drain" or
        tag[0] == "Vaults of Vaarn" or tag[0] == "Dungeoneering" or
        tag[0] == "Whitehack" or
        tag[0] == "The Vast in the Dark" or
        tag[0] == "Wicked Ones" or
        tag[0] == "Nuctemeron" or tag[0] == "Marrow & Splinters" or
        tag[0] == "Dancing with Bullets Under a Neon Sun" or
        tag[0] == "Mothership: Gradient Descent" or
        tag[0] == "Neverland: A Fantasy Role-Playing Setting" or
        tag[0] == "Rogueland" or
        tag[0] == "The Scourge of the Scorn Lords" or
        tag[0] == "Twilight: 2000" or
        tag[0] == "Ironsworn: Starforged" or
        tag[0] == "Ironsworn Worlds" or tag[0] == "Ironsworn Worlds: Sundered Isles" or
        tag[0] == "Starforged" or
        tag[0] == "Barrowmaze" or 
        tag[0] == "Forbidden Lands" or
        tag[0] == "T-DEF" or tag[0] == "Mörk Borg" or
        tag[0] == "RISE" or tag[0] == "DELVE" or
        tag[0] == "UMBRA" or tag[0] == "WASTE" or
        tag[0] == "Descent Into The Abyss" or
        tag[0] == "Ex Novo" or tag[0] == "Ex Umbra" or
        tag[0] == "Under Ashen Skies" or
        tag[0] == "Mapping the Catacombs" or
        tag[0] == "Old-School Essentials" or
        tag[0] == "The Nightmares Underneath" or
        tag[0] == "A Cool and Lonely Courage" or
        tag[0] == "Dead Halt" or
        tag[0] == "Tunnel Goons" or
        tag[0] == "Lancer" or
        tag[0] == "Sleepaway" or
        tag[0] == "The Ultraviolet Grasslands" or
        tag[0] == "Four Against Darkness" or
        tag[0] == "Dyson's Delve" or
        tag[0] == "Labyrinth Lord" or
        tag[0] == "Mothership" or 
        tag[0] == "Mothership: Dead Planet" or 
        tag[0] == "Mothership: A Pound of Flesh" or
        tag[0] == "OSR" or 
        tag[0] == "One Page Dungeon" or 
        tag[0] == "Rol" or
        tag[0] == "Shinobi & Samurai" or
        tag[0] == "Strange Nations" or 
        tag[0] == "Swarp Swords & Sinister Spells" or 
        tag[0] == "The Black Isle" or
        tag[0] == "Veinscrawl" or
        tag[0] == "Seekers Beyond The Shroud" or
        tag[0] == "A Rasp of Sand" or
        tag[0] == "Ruins of the Undercity" or
        tag[0] == "Mad Monks of Kwantoom" or
        tag[0] == "Solar Blades & Cosmic Spells" or
        tag[0] == "Ironsworn" or
        tag[0] == "Winter's Daughter" or
        tag[0] == "The Hole in The Oak" or
        tag[0] == "Trilemma Adventures"  or
        tag[0] == "Zine Quest" or tag[0] == "Zine Quest 3" or
        tag[0] == "Zine Quest 2" or
        tag[0] == "A Thousand Year Old Vampire" or
        tag[0] == "A Torch in the Dark" or
        tag[0] == "Alone Among the Stars" or
        tag[0] == "Beak, Feather & Bone" or
        tag[0] == "Pico, Pluma & Hueso" or
        tag[0] == "Cuentos de ánimas" or
        tag[0] == "Disciples of Bone and Shadow" or
        tag[0] == "Disciples of Bone and Shadow: Conquered Sun Edition" or
        tag[0] == "Do Not Let Us Die In The Dark Night Of This Cold Winter" or
        tag[0] == "English Eerie" or
        tag[0] == "Malditos" or
        tag[0] == "Mythic" or
        tag[0] == "Nadir" or
        tag[0] == "Non Gratus Rodentum" or
        tag[0] == "Oneironaut" or
        tag[0] == "Quill" or
        tag[0] == "SCRAWL" or
        tag[0] == "Scarlet Heroes" or
        tag[0] == "Sigils in the Dark" or
        tag[0] == "The Adventure Crafter" or
        tag[0] == "The Adventurer" or
        tag[0] == "The Metamorphica Revised" or
        tag[0] == "The Perilous Wilds" or
        tag[0] == "The Quest" or
        tag[0] == "The Wretched" or
        tag[0] == "Tome of Adventure Design" or
        tag[0] == "UNE" or
        tag[0] == "Wilderness Hexploration" or
        tag[0] == "D30 Sandbox Companion" or
        tag[0] == "Blades in the Dark" or
        tag[0] == "Ironsworn: Delve" or
        tag[0] == "Mausritter" or
        tag[0] == "Troika" %}
        <span class="label label-danger"><strong>#<a class="tag-color"
        href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></strong></span> 
    {% else %}
        {% if tag[0] == "9 Card Game Print & Play Design Contest" or
            tag[0] == "Charles S. Roberts Awards" or
            tag[0] == "Golden Geek" or
            tag[0] == "Solitaire Print & Play Design Contest" or
            tag[0] == "Wargame Print & Play Design Contest" or
            tag[0] == "Spiel des Jahres" or
            tag[0] == "Ennie" %}
            <span class="label label-success"><strong>#<a class="tag-color"
            href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></strong></span> 
        {% else %}
            {% if tag[0] == "Campaña" or tag[0] == "Expansión" or
            tag[0] == "Kickstarter" or tag[0] == "Print & play" or
            tag[0] == "Tabletopia" or tag[0] == "Tops" or
            tag[0] == "Verkami" or tag[0] == "Gamefound" or
            tag[0] == "Traducciones" or
            tag[0] == "Boletín Informativo Solitario" or
              tag[0] == "El mes en juegos" %}
                <span class="label label-warning"><strong>#<a class="tag-color"
                href="/etiqueta/{{tag[0] | slugify: "latin"}}">{{tag[0]}}</a></strong></span> 
            {% else %}
                {% if tag[0] == "GenCon"
                or tag[0] == "Spiel Digital"
                or tag[0] == "Essen Spiel"
                or tag[0] == "Essen Spiel 2019"
                or tag[0] == "Essen Spiel 2021"
                or tag[0] == "UKGE" %}
                    <span class="label label-info"><strong>#<a class="tag-color"
                    href="/etiqueta/{{tag[0] | slugify:
                    "latin"}}">{{tag[0]}}</a></strong></span> 
                {% else %}
                    {% if
                        tag[0] == "Compass Games" or 
                        tag[0] == "Decision Games" or
                        tag[0] == "GMT Games" or
                        tag[0] == "Hollandspiele" or
                        tag[0] == "Lock 'n Load Publishing" or
                        tag[0] == "Multi-Man Publishing" or
                        tag[0] == "NAC Wargames" or
                        tag[0] == "Revolution Games" or
                        tag[0] == "VUCA Simulations" or
                        tag[0] == "White Dog Games" or
                        tag[0] == "Worthington Publishing" or
                        tag[0] == "Across the Bug River: Volodymyr-Volynskyi 1941" or
                        tag[0] == "Advanced Squad Leader: Starter Kit" or
                        tag[0] == "All Bridges Burning" or
                        tag[0] == "Ambon: Burning Sun & Little Seagulls" or
                        tag[0] == "Ardennes 44" or
                        tag[0] == "Cataclysm: A Second World War" or
                        tag[0] == "Caesar: Rome vs. Gaul" or
                        tag[0] == "Crossing the Line: Aachen 1944" or
                        tag[0] == "El Imperio del Sol" or
                        tag[0] == "Empire of the Sun" or
                        tag[0] == "Exploradores de las Profundidades Sombrías" or
                        tag[0] == "Fields of Fire" or
                        tag[0] == "Five Parsecs From Home" or
                        tag[0] == "Gettysburg" or
                        tag[0] == "Great War Commander" or
                        tag[0] == "Hannibal's Revenge" or
                        tag[0] == "Hitler's Reich" or
                        tag[0] == "Nevsky: Teutons and Rus in Collision" or
                        tag[0] == "Pavlov's House" or
                        tag[0] == "Peloponnesian War" or
                        tag[0] == "Rangers of Shadow Deep" or
                        tag[0] == "Red Dust Rebellion" or
                        tag[0] == "Santander 37" or
                        tag[0] == "Sniper Kill Confirmed" or
                        tag[0] == "Space Empires" or
                        tag[0] == "Stalingrad 42" or
                        tag[0] == "The Dark Valley" or
                        tag[0] == "he Last Hundred Yards" or
                        tag[0] == "The Last Hundred Yards: Airborne Over Europe" or
                        tag[0] == "he Plum Island Horror" or
                        tag[0] == "The Pure Land" or
                        tag[0] == "The Shores of Tripoli" or
                        tag[0] == "Thunder in the East" or
                        tag[0] == "Triumvir" or
                        tag[0] == "Versailles 1919" or
                        tag[0] == "World at War 85: Storming the Gap" %}
                        <span class="label label-grey"><strong>#<a class="tag-color"
                    href="/etiqueta/{{tag[0] | slugify:
                    "latin"}}">{{tag[0]}}</a></strong></span> 
                {% else %}
                    <span class="label label-primary"><strong>#<a class="tag-color"
                    href="/etiqueta/{{tag[0] | slugify:
                    "latin"}}">{{tag[0]}}</a></strong></span> 
                {% endif %}
                {% endif %}
            {% endif %}
        {% endif %}
   {% endif %}
{% endfor %}
</p>

### Categorías

En esta sección tienes ordenadas las entradas del blog por categoría:

<p>{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
<a href="#{{ category[0] }}">{{ category[0] }}</a>{% if forloop.last == false
%},{% endif %}{% endfor %}</p>


{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
  <h4 id="{{ category[0] }}">{{ category[0]}}</h4>
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


