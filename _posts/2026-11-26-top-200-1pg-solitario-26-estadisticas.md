---
layout: post
title: "Las estadísticas del Top 200 del 1-Player Guild de 2026"
date: 2026-11-26
categories: [Listas]
tags: [Tops]
imghtml: https://live.staticflickr.com/65535/55674991520_898a1cb6d8_c.jpg
post_desc: "Os traigo las estadísticas del Top 200 de juegos en
solitario del 1-Player Guild de Board Game Geek"
---

![](https://live.staticflickr.com/65535/55674991520_898a1cb6d8_c.jpg)

<hr>

En esta entrada os recojo los datos estadísticos de los
[resultados](https://boardgamegeek.com/geeklist/387123/2026-peoples-choice-top-solo-games-1-300)
**Top 200 de 1-Player Guild de 2026** con una serie de gráficas interactivas, si
buscáis un resumen de cuáles han sido los juegos más votados [os redirijo a esta
entrada]({{site.baseurl}}/2026/11/22/top-200-1pg-solitario-26/).

Los datos de estas gráficas se han recogido con una serie de scripts que
usan la [API de BGG](https://boardgamegeek.com/wiki/page/BGG_XML_API2), hay
algunos datos que pueden variar en el tiempo, por ejemplo la complejidad de los
juegos, ya que es un valor no cerrado y los usuarios de BGG pueden votar o
cambiar su voto en cualquier momento. Otras veces, el usuario encargado de
colocar los juegos en la lista cambia el juego visible en la entrada de la
lista, en ese caso, los datos se obtuvieron el 20 de Noviembre de 2026, por lo
que cambios posteriores no han sido reflejados.

Como también sabréis, a la hora de hacer el recuento de votos hay algunos
juegos que se [agrupan](https://boardgamegeek.com/geeklist/343005/groupings-made-for-the-top-200-solo-games-peoples)
y se cuentan como si se estuviera votando a un mismo
juego; por ejemplo, *Agricola* engloba todos los votos dados al propio
*Agricola* y a: *Agricola (Revised Edition)*, *Agricola: Family Edition*,
*Agricola: All Creatures Big and Small*, *Agricola: All Creatures Big and Small
– The Big Box*, *Agricola 15* y *Agricola: Special Edition*.

En base a esto, hay algunas gráficas que van a sufrir algún desfase de
datos ya que las agrupaciones no siguen un patrón consistente, a veces se toma
como juego de la lista el más nuevo, otras veces el primero del "sistema"... no
hay patrón. Estos son los apuntes que quiero dar respecto a esto:

1. En el caso de [Juegos por complejidad](#juegos-por-complejidad) se toma la
complejidad del juego que aparece en la lista, aunque los juegos agrupados
tengan complejidad diferente; por ejemplo, todas las entregas de [Great Western
Trail](https://boardgamegeek.com/boardgamefamily/54030/game-great-western-trail)
están agrupadas bajo *Great Western Trail: Second Edition*, con 
complejidad de 3.7, aunque la complejidad suba a 3.99 en *Great Western Trail:
New Zealand*. 

2. En el caso de [Juegos por año de
publicación](#juegos-por-año-de-publicación) también se toma el año de
publicación del juego que aparece en la lista. En las agrupaciones a veces se
utiliza el juego más nuevo de la serie para representar a a la serie y otras
veces el más viejo. No hay patrón ni razón aparente. Por ejemplo, los juegos de
la serie [HEXplore
It](https://boardgamegeek.com/boardgamefamily/57188/game-hexplore-it) aparecen
agrupados bajo *HEXplore It: The Mountains of Godai*, última entrega de la
serie (y también la menos popular), mientras que como os he comentado arriba,
todos los juegos de la serie de *Great Western Trail* están agrupados bajo
*Great Western Trail: Second Edition*, publicado en 2021, aunque la última
reimplementación de la serie sea *Great Western Trail: New Zealand* de 2023.

3. En el caso de [Juegos por editorial](#juegos-por-editorial), si las
editoriales han cambiado a lo largo de la vida del juego, o si los juegos
agrupados han sido publicados por diferentes editoriales, los scripts se van a
quedar con la primera editorial que aparece en el juego de la lista.

Ahora que ya he dado mis avisos para navegantes, os dejo con las estadísticas.

## Estadísticas del Top 200 de 1-Player-Guild

- [Juegos por complejidad](#juegos-por-complejidad)
- [Juegos por año de publicación](#juegos-por-año-de-publicación)
- [Juegos por autor](#juegos-por-autor)
- [Juegos por artista](#juegos-por-artista)
- [Juegos por editorial](#juegos-por-editorial)


En las gráficas con mucho dato **es recomendable usar un dispositivo con pantalla
grande** para que sea más fácil poder colocar el cursor en el dato concreto. Si
pasáis el cursor por encima vais a poder ver el dato concreto que da valor a
ese punto de la gráfica.

### Juegos por complejidad 

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRrIhEreDlEPj93d-UnHUpUENvWf8zqj4E6PypwpH2KbKSSKCFnU_nJFDZtahF7-Jf2tKr2H3rqflRp/pubhtml?gid=676840357&single=true"></iframe>
</div>

El primer factor interesante de los juegos en el Top es su complejidad. La
"complejidad" se refiere a cómo de complicado es un juego de entender y/o
cuánto te hace pensar. En base a esto, BGG considera que un juego es de "peso
duro" si tiene muchas reglas y tienes que pensar mucho antes de tomar una
acción y de "peso ligero" si el reglamento es corto y/o tienes que pensar poco
antes de tomar acciones. Los valores de "peso" que puede tener un juego son:
Ligero (1), medio-ligero (2), medio (3), medio-pesado (4) y pesado (5). Los
usuarios de BGG son libres de puntuar los juegos en base a esa escala, BGG hace
una media y eso se utiliza para determinar el valor de complejidad de un juego.

Al igual que otros años, los juegos se concentran en peso *medio* (76),
*medio-ligero* (61) y *medio-pesado* (55), si demasiada diferencia entre los
tres valores. Son los juegos *ligeros* (3) y *pesados* (5) los más raros.

El juego más pesado de la lista es [High Frontier 4
All](https://boardgamegeek.com/boardgame/281655/high-frontier-4-all) con 4.8 de
complejidad; el menos pesado es [A Gentle
Rain](https://boardgamegeek.com/boardgame/334011/a-gentle-rain) con 1.11
de complejidad.

El peso [medio](https://es.wikipedia.org/wiki/Media_aritm%C3%A9tica) de los
juegos es 3.01. La
[mediana](https://es.wikipedia.org/wiki/Mediana_(estad%C3%ADstica)) de
complejidad es 2.93, con juegos como [Terraforming Mars: Ares
Expedition](https://boardgamegeek.com/boardgame/328871/terraforming-mars-ares-expedition), 
[Endeavor: Deep
Sea](https://boardgamegeek.com/boardgame/367966/endeavor-deep-sea) y [Las
Ruinas Perdidas de Arnak](https://boardgamegeek.com/boardgame/312484/lost-ruins-of-arnak). 

### Juegos por año de publicación

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQXdcUBHXktk8TymAPU-9lwHvyaZ-z-z3YJKmW3to4mwaJHBWrmBJKN8wy2Uy8RNwAp5if1mNzsWxO7/pubhtml?gid=852204170&single=true"></iframe>
</div>

Pasándonos al número de juegos en el Top en base a su año de publicación, la
mayoría de los juegos del top concentran en los años 2017 a 2025, siendo 
2025 el año más prolífico con 25 juegos publicados.

Podéis ver cuáles han sido los cuatro juegos de 2026 que han llegado al top en
la entrada del [Top 200 de 1PG de 2026]({{site.baseurl}}/2026/11/22/top-200-1pg-solitario-26/#las-novedades-en-el-top-200).

### Juegos por autor

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6ZqyDHXJGxSlGi1adiOQw0DL3vs5FLRatS22Z-F8Qg6cwGzCy1psdju2Pc1g3T8Np0vDLbiEwsOkq/pubhtml?gid=137265108&single=true"></iframe>
</div>


<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6ZqyDHXJGxSlGi1adiOQw0DL3vs5FLRatS22Z-F8Qg6cwGzCy1psdju2Pc1g3T8Np0vDLbiEwsOkq/pubhtml?gid=196837108&single=true"></iframe>
</div>

En esta sección tenéis dos gráficas, la primera tiene todos los autores que han
publicado juegos que se encuentren en el top, la segunda solamente recoge los
autores que han publicado al menos dos juegos que se encuentren en el Top 200.

El autor con más juegos es **Shem Phillips** con 9 juegos en el top, el señor
Phillips publica juegos con su editorial **Garphill Games**, que también veréis
en posiciones muy altas en la sección de [Juegos por
editorial](#juegos-por-editorial); **Uwe Rosenberg** 
se encuentra en segunda posición con 7 juegos en el top, finalmente, el bronce
se lo lleva **Josh J. Carlson** con 6 juegos.

La primera persona no hombre que aparece en el top es **Nikki Valens** (se
[identifica](https://boardgamegeek.com/boardgamedesigner/69718/nikki-valens)
como they/them) con 4 juegos publicados (*Arkham
Horror*, *Gloomhaven: Buttons & Bugs*... ), después tenemos a **Elizabeth
Hargrave** (*Wingspan*, *Wingspan Pocket*...) con 2 juegos publicados, el resto
de autoras tienen 1 juego publicado en el top.

En cuanto a autores nacionales (me guío por el idioma de los nombres, si hay
algún error, es mío), tenemos un empate de **Benjamín Amorín**  autor de [Ace of
Spaces](https://boardgamegeek.com/boardgame/429861/ace-of-spades), e
**Isra C.** y **Shei S.**, autores de [The White
Castle](https://boardgamegeek.com/boardgame/371942/the-white-castle); ambos con
un juego en el Top 200.

En total, tenemos 229 autores diferentes.

### Juegos por artista

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTGa9ERco99Pkol7JSRpCyGm7tMOF_rGQ57Zno0UuRtjiYWIVllJsWTsod1Bhp2ZKpBqvujsqpftG8U/pubhtml?gid=1117052645&single=true"></iframe>
</div>

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTGa9ERco99Pkol7JSRpCyGm7tMOF_rGQ57Zno0UuRtjiYWIVllJsWTsod1Bhp2ZKpBqvujsqpftG8U/pubhtml?gid=856757616&single=true"></iframe>
</div>

Una de las novedades de este año es que he recogido también quiénes son los
artistas que firman el apartado visual de los juegos. En total, tenemos 494
artistas diferentes, por lo que la letra es algo pequeña en las gráficas. Al
igual que en la sección anterior, la primera gráfica tiene la lista de todos
los artistas, mientras que en la segunda tenemos los que han participado en al
menos dos juegos.

En la cabeza de la gráfica se encuentra **Mihajlo Dimitrievski**, conocido
también como "The Mico", que firma 7 juegos que se encuentran en Top; este
ilustrador es conocido por ilustrar la mayoría de los juegos de **Garphill
    Games**. Luego tenemos un triple empate con 6 juegos cada uno de 
**Dennis Lohausen**, que ha trabajado entre otras cosas en *Ark Nova*,
*Gaia Project* y *A Feast for Odin*; **Ewa Labak**, artista de *Nemesis*, *ISS
Vanguard* y *Grimcoven*, entre otros muchos trabajos; y **Patryk Jędraszek**
que comparte también los juegos en los que ha trabajado la señora Labak.

En cuanto a la representación de personas que no sean hombres, aquí ya tenemos
a **Ewa Labak** en el triple empate por la segunda posición del que os he
hablado arriba, **Magali
Villeneuve** (*Star Wars: The Deckbuilding Game*, *The Lord of The Rings: The
Card Game*...) con 5 juegos, **Beth Sobel** (*Wingspan*, *Cascadia*...) con 3
juegos, y muchas otras más.

En la lista tenemos muchos artistas que tienen nombre y apellidos en español,
por lo que intuyo que habrá alguno de España, además de nuestros compadres
latinoamericanos.

### Juegos por editorial

<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSI5Z59lAQsN2raimpJXbL6eWIlrTiminDuyi_TSZRl297NTtQhjZmenLRgCc0GDsQeD4DRyELZ3Nfl/pubhtml?gid=333525587&single=true"></iframe>
</div>


<div align="center">
<iframe style="width: 100%;" height="450px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSI5Z59lAQsN2raimpJXbL6eWIlrTiminDuyi_TSZRl297NTtQhjZmenLRgCc0GDsQeD4DRyELZ3Nfl/pubhtml?gid=1409804607&single=true"></iframe>
</div>

Finalmente, tenemos la sección de juegos por editorial, aquí también tenéis dos
gráficas, en la primera aparecen todas las editoriales mientras que en la
segunda solamente salen las editoriales que tienen al menos dos juegos en el
Top 200. 

Debido a que ya tenemos muchas editoriales españolas que publican juegos de
autoría propia y que tienen relevancia internacional, este año no voy a
analizar qué editoriales "traductoras" son las que más juegos tienen en el Top.

Como podéis observar, la editorial con más juegos publicados es **Fantasy
Flight Games**, con 13 juegos, seguida de **Garphill Games** con 11 juegos, y
en tercera posición se encuentra **Stonemaier Games**, con 7 juegos.

Entre las editoriales españolas, tenemos un empate de **Devir** y **Salt &
Pepper Games** con 2 juegos publicados cada una; la primera tiene a [The White
Castle](https://boardgamegeek.com/boardgame/371942/the-white-castle) y a [Ace
of Spades](https://boardgamegeek.com/boardgame/429861/ace-of-spades), la
segunda a [Conservas](https://boardgamegeek.com/boardgame/402024/conservas) y
[Witchcraft!](https://boardgamegeek.com/boardgame/383499/witchcraft), que es
una reimplementación del
[Resistid!](https://boardgamegeek.com/boardgame/352697/resist), del que tenéis
un [análisis aquí]({{site.baseurl}}/2023/06/04/analisis-resistid/). Estas
editoriales van seguidas por **Ludonova**, con 1 juego en el top, que es
[Adamastor](https://boardgamegeek.com/boardgame/448435/adamastor).

En total hay 116 editoriales distintas con juegos en el Top este año.

## Conclusiones

Estos han sido los datos estadísticos de este año del **Top 200 de 1-Player
Guild**.  Tendremos que ver cómo se desarrolla la tendencia de que las
editoriales españolas sean relevantes en el Top 200, además todavía nos faltan
autores (¡y autoras!) españolas en el Top 200. 

Finalmente, este año ha habido una falta tremenda de wargames en el Top 200,
con mi granito de arena yo también me adjudico parte de la culpa, ya que al no
jugar a wargames este último año, tampoco he votado a ninguno en mi
Top 20. Espero que de cara al año que viene pueda considerar votar a alguno.

Esto es todo, espero que os haya parecido interesante. ¡Os leo en los
comentarios o en redes!
