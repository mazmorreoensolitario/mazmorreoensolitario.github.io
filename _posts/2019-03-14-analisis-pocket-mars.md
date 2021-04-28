---
layout: post
title: "Análisis - Pocket Mars"
date:   2019-03-14
categories: [Análisis]
tags: [Pocket Mars]
score: 4
game: "Pocket Mars"
imghtml: https://raw.githubusercontent.com/mazmorreoensolitario/public-images/master/analisis/pocket-mars.png
post_desc: "El futuro en la Tierra es incierto. Nos han encargado preparar una
infraestructura viable para la vida en Marte que ayude a que mas colonos puedan 
trasladarse al planeta Rojo, pero nuestra competencia, la compañía Devious 
Automatics (DA) cree que puede comprometerse a hacer la colonización de Marte 
más eficiente con su tecnología basada en robots. Como expertos en eficiencia 
de proyectos, vamos a demostrar que están equivocados."
---

<div class="panel panel-primary">
    <div class="panel-heading">
        <h3 class="panel-title">Ficha técnica - Pocket Mars</h3>
    </div>
    <div class="panel-body">
        <div class="col-md-6 post-img">
            {% if page.imghtml %}
            <img width="400" src="{{page.imghtml}}"
                alt="{{page.title}}">
            {% else %}
            <img width="400" src="{{site.baseurl}}/images/{{page.img}}"
                alt="{{page.title}}">
            {% endif %}
        </div>
        <div class="col-md-6">
        <table class="table table-striped table-hover">
            <tr><td class="text-left"><strong>Fecha de salida:</strong></td><td class="text-left">2017</td></tr>
            <tr><td class="text-left"><strong>Precio:</strong></td><td class="text-left"><a href="https://amzn.to/2UzgdND">21€</a>
            (Inglés), <a
            href="https://amzn.to/2P19tqS">15€</a>
            (Español)</td></tr>
            <tr><td class="text-left"><strong>Número de jugadores:</strong></td><td class="text-left">1-4</td></tr>
            <tr><td>Modo en solitario con bot</td><td></td></tr>
            <tr><td class="text-left"><strong>Tiempo de juego:</strong></td><td class="text-left">20-30 mins</td></tr>
            <tr><td class="text-left"><strong>Idioma:</strong></td><td class="text-left">Español / Inglés</td></tr>
         </table>
        </div>
        <div class="col-md-12"></div>
        <div class="col-md-12">
         <ul>
             <li>
                 Diseñado por Michał Jagodziński, ilustraciones de Jarosław Wajs.
             </li>
             <li>
                 Ha sido editado por <a href="https://boardanddice.com/">Board
                 & Dice</a> y a España nos llega por <a
                 href="https://2tomatoesgames.com/">2Tomatoes Games</a>.
             </li>
             <li>
                 El tamaño de la caja es perfecto para el contenido del juego y
                 si tenéis la edición inglesa (la española no lo sé), todo está
    hecho en Polonia, así que mucho mejor.
             </li>
         </ul>
         </div>
    </div>
</div>

En esta entrada os vais a encontrar fotografías con las cartas del juego en
inglés (el juego es de 2017 y a España no llegó hasta 2018), y puesto que no he 
podido encontrar el manual en español en internet, voy a traducir ciertos 
nombres de las cartas como a mí mejor me parece, que puede que no se
corresponda con la traducción oficial que ha hecho el equipo de 2Tomatoes 
Games.

### Información general

<p align="center"><img src="https://farm8.staticflickr.com/7866/40413269853_821b139146_c.jpg"></p>
<p align="center"><small>A colonizar Marte se ha dicho</small></p>

El futuro en la Tierra es incierto. Nos han encargado preparar una
infraestructura viable para la vida en Marte que ayude a que mas colonos puedan
trasladarse al planeta Rojo, pero nuestra competencia, la compañía Devious
Automatics[^1] (DA) cree que puede comprometerse a hacer la colonización de Marte
más eficiente con su tecnología basada en robots. Como expertos en eficiencia
de proyectos, vamos a demostrar que están equivocados.

Para demostrar a DA que nuestra compañía es mejor, hemos diseñado un sistema de
simulaciones llamado **Pocket Mars** que vamos a usar para competir contra sus
robots... pero de momento nadie ha sido capaz de superarles. 

**[Pocket Mars](https://boardgamegeek.com/boardgame/223779/pocket-mars)** es un
juego de control de área en el que tendremos que conseguir colocar el mayor
número de colonos espaciales posibles en una serie de edificios diseñados con
funciones específicas para que los humanos sobrevivamos en Marte.

El la partida tenemos en juego cinco edificios distintos con una función
especial:  Ecosistema, Energía, Ciencia, Gestión de Agua y  Construcción; a los
que tendremos que hacer llegar colonos desde nuestra nave espacial. Empezaremos
con un único colono en nuestra nave y los seis restantes se encontrarán en la
Tierra. Para mover colonos de nuestra nave a los edificios de Marte, tendremos
que hacer uso de cartas de proyecto, estas cartas de proyecto tienen un número
y pueden jugarse en un edificio específico de los que se encuentran en Marte.

Cuando se juega una carta de proyecto, se compara el número que tiene la carta
con la última carta jugada en el edificio o bien, si aún no hay cartas jugadas,
con el número por defecto que tiene el edificio.
Si el número de la carta de proyecto  que jugamos es superior, podremos mover
uno de nuestros colonos de la nave al edificio. Después, podremos activar la
función especial del edificio, como mover un colono desde la Tierra a mi nave, 
mover colonos entre edificios, descartar cartas, ganar energía etc. y
finalmente podremos activar la función especial de la carta que hemos jugado.

Las funciones especiales de las cartas están *algo* temáticamente ligadas con la
función que el edificio debería efectuar, por ejemplo solo podremos ganar
energía con cartas de proyecto del edificio de Energía; pero salvo este
ejemplo, el resto de cartas no tienen temática. Por lo que se puede asociar
cada edificio a un palo diferente y no hay más profundidad temática que eso.

De las cartas que podemos jugar, tendremos como máximo cuatro, de las cuales
dos estarán en nuestra mano y dos en el llamado *módulo de preparación*, las
cartas tienen efectos diferentes si se juegan de la mano o del módulo,
concretamente, las que se juegan desde la mano se van a la pila de descartes
tras usarse, por lo que no se colocan en el edificio, no podremos colocar
colonos ni activar la función del edificio.

Nuestro autómata rival tendrá dos cartas boca abajo en su módulo de
preparación, que podremos usar sin mirar, la carta restante de su módulo
determinará el edificio en el que coloca colonos desde su nave. Cabe destacar
que el autómata no juega cartas, solo se utilizan para determinar en qué
edificio coloca los colonos. Finalmente, las funciones especiales de los
edificios cambian para el autómata, tienen unas funciones específicas diseñadas
para él.

La partida termina cuando no se puedan robar más cartas para el módulo del
autómata, cuando hemos colocado todos nuestros colonos o cuando el autómata ha
colocado todos sus colonos. Tendremos que contar puntos en base a los colonos
colocados, los que hayamos conseguido traer desde la Tierra, el nivel de
energía que tengamos en nuestra nave y nos darán varias bonificaciones por 
mayorías. 

**¡Vamos a prepararnos para un juego de Mazmorreo en solitario!**

### Preparación

<p align="center"><img src="https://farm8.staticflickr.com/7871/40413269373_78dd40f5a6_c.jpg"></p>
<p align="center"><small>Pocket Mars preparado para jugar. Arriza a la
izquierda está el mazo de cartas de Proyecto seguido de los 5 edificios del
juego: Ciencia, Ecosistema, Gestión de Agua, Energía y Construcción. En la
parde de abajo a la izquierda la mano del jugador y dos cartas en el Módulo de
Preparación del jugador encima de la nave del jugador. A la derecha la nave y
el Módulo de Preparación (con cartas boca abajo) del autómata</small></p>


* Elegimos una nave espacial para nosotros y otra para el autómata y las
  colocamos sobre la mesa. Colocamos una ficha de energía en el 1 en cada
  nave, este es el nivel de energía inicial.
  
* Cogemos 1 colono de nuestro color y lo colocamos sobre nuestra nave, el resto
  de colonos de nuestro color se dejan a mano sobre la mesa, en un sitio que
  represente la Tierra.
  
* El autómata coge 5 colonos de su color y los coloca sobre su nave, los 2
  colonos de su color restantes se colocan en la Tierra.
  
* Colocamos los 5 Edificios de Marte en una fila sobre la mesa.

* Barajamos las cartas de Proyecto y las colocamos en un montón dejando espacio
  para una pila de descartes.
  
* Robamos sin mirar 2 cartas y las colocamos boca abajo delante de la nave
  del autómata, estas dos cartas forman su Módulo de Preparación.
  
* Robamos 4 cartas para nosotros, elegimos 2 para colocar delante de nuestra
  nave y así formar nuestro Módulo de Preparación, las 2 cartas restantes
  formarán nuestra mano.
 
### Empezando a jugar

Como podéis ver el autómata empieza con ventaja ya que tiene 5 colonos
preparados para colocar en los diferentes Edificios, nosotros sin embargo,
empezamos solamente con 1. Salvo que lo indique alguna carta **no** podemos
mover colonos desde la Tierra a Marte, siempre tendrán que pasar antes por
nuestra nave.

<p align="center"><img src="https://farm8.staticflickr.com/7875/40413268753_8f6948ab8d_c.jpg"></p>
<p align="center"><small>Dos cartas de Proyecto, de Ciencia a la izquierda y de
Energía a la derecha. Ambas cartas tienen un valor de 5. En la parte inferior
están las acciones que se ejecutan desde la mano (arriba) y desde el Módulo
(abajo)</small></p>


**Cartas de Proyecto.** Las cartas de Proyecto tienen dos áreas importantes
(ver imagen de arriba). En
la parte superior, tanto a la izquierda como a la derecha, aparecerá el valor
de la carta. En la parte inferior está el área de acciones, divida en dos
partes; por un lado, en la parte superior tenemos la acción que
podemos hacer si jugamos la carta de nuestra mano (hay un iconito de una mano),
por otro lado, en la parte inferior está representada la acción que podemos
ejecutar si jugamos la carta desde los Módulos de Preparación, tanto del
autómata como del nuestro (viene representada por un iconito de un cuadrado con
las esquinas en negrita). Explicamos cómo jugar las cartas más abajo.

<p align="center"><img src="https://farm8.staticflickr.com/7838/40413268393_07b0680506_c.jpg"></p>
<p align="center"><small>Cartas de Edificio, de Ecosistema a la izquierda y de
Gestión de Agua a la derecha. El valor por defecto de los Edificios es 3. Abajo
están los espacios para colocar los colonos.</small></p>


**Edificios en Marte.** Las cartas de Edificio tienen tres áreas (ver imagen de
arriba). Arriba y de
izquierda a derecha tenemos el icono del tipo de edificio, la función especial
que podemos ejecutar tras colocar un colono y el valor por defecto del
edificio (siempre 3). Abajo está el área de colocación de colonos, en la región de la
izquierda no hay límite de colonos, el la zona de la derecha sólo podrá
colocarse un único colono (la zona de la derecha nos da 4 Puntos de Victoria
frente a los 2 que nos da la zona de la izquierda).

**Estructura de la partida.**
Como hemos comentado brevemente antes, el juego tiene una duración de rondas
ilimitado, la partida se acabará cuando el autómata o nosotros hayamos colocado
todos nuestros colonos, o bien cuando no podamos robar más cartas para el
Módulo de Preparación del autómata.

Cada turno tiene la siguiente estructura: *Fase de arquitecto*, *Fase de fallo
del sistema*, *Fase de activación del autómata*.

#### 1. Fase de arquitecto

<p align="center"><img src="https://farm8.staticflickr.com/7876/40413269023_c4af66dcd7_c.jpg"></p>
<p align="center"><small>Mano y Módulo de Preparación del jugador.</small></p>

En esta fase jugamos nosotros, y podemos elegir hacer una de las siguientes
cinco acciones:

1. **Jugar una carta de Proyecto de nuestra mano.** Al jugar una carta de
   Proyecto de nuestra mano, nos fijamos en el icono de mano, en la mitad
   superior del recuadro de acciones. Podremos ejecutar esta acción. Después
   la carta va inmediatamente a la pila de descartes.

2. **Jugar una carta de Proyecto de nuestro Módulo de Preparación.** Para
   ejecutar esta acción tendremos que comprobar tres cosas:
   
   * Primero colocamos la carta debajo del edificio, comparando el valor
    de la carta contra el valor de la última carta en juego en ese Edificio (o
    el valor por defecto del Edificio si no hay cartas en juego). Si el valor
    es mayor podremos mover uno de nuestros colonos **a la zona de la
    izquierda** del Edificio.
    
     Por ejemplo, tomando como mano de ejemplo la que
    se muestra en la imagen de arriba, vamos a jugar la carta de Gestión de
    Aguas de valor 7 del Módulo. En el Edificio de Gestión de Agua no hay nada
    aún colocado y el valor por defecto del Edificio es 3. Como 7 es mayor que
    3 colocamos al colono de nuestra nave espacial en el Edificio.
    
   * Después podremos (o no) activar la acción de la carta de Proyecto. Tenemos
     que fijarnos en la acción de abajo del todo, la de los Módulos de
     Preparación.
        
     Siguiendo el ejemplo, el efecto de la carta es "Coge un Colono de la
     Tierra si Tienes una carta de Proyecto de Gestión de Agua en la Mano". En
     nuestra mano tenemos 1 carta de Gestión de Agua y otra carta de
     Construcción, así que podríamos aplicar el efecto si queremos. Nos viene
     bien, así que lo aplicamos.
     
   * Finalmente activamos (o no) el efecto especial del Edificio en el que
     acabamos de jugar la carta.
     
     Siguiendo el ejemplo, esta vez tenéis que mirar dos imágenes hacia arriba,
     el Edificio de Gestión de Agua nos permite poner una carta de nuestra mano
     o Módulo en la parte de abajo del mazo de cartas de Proyecto. Como no nos
     interesa hacer eso, no activamos el Efecto.
     
   **En el edificio de Construcción** (el negro) **no se pueden colocar
     colonos**. Todo funciona igual que lo descrito anteriormente, salvo que no
     se pueden colocar colonos.

3. **Jugar una carta de Proyecto del Módulo de Preparación del autómata.** Esa
   acción es similar a la de jugar una carta de nuestro Módulo. Elegimos una de
   las dos cartas boca abajo del Módúlo del autómata y la jugamos, también
   tenemos que comprar los valores y movemos **uno de nuestros colonos** a la
   zona de la izquierda del Edificio si el valor es superior, solo que **no** 
   se activa el efecto de la carta, y **sí** se activa la habilidad del
   edificio.

4. **Coger uno de nuestros colonos desde la Tierra.** Cogemos un colono desde
   la Tierra y descartamos 1 carta de Proyecto del Módulo del autómata. Si no
   hay de nuestros colonos en la Tierra, entonces esta acción no puede
   ejecutarse.
   
5. **Ganar 2 de energía.** Ganamos 2 de energía a costa de descartar una carta
   de nuestra mano o de nuestro Módulo, actualizamos el nivel de energía
   inmediatamente en nuestra nave.

**Regla de las 4 cartas.** Después de usar nuestra acción tenemos que volver a
tener una mano de 2 cartas y tener 2 cartas en el Módulo de Preparación.
Para eso tenemos que **robar cartas del Módulo de Preparación del autómata**.
Solamente si no hay cartas en el Módulo del autómata podremos robar del montón 
de cartas de Proyecto. Una vez que pongamos una carta en nuestro Módulo **no** 
podrá volver a nuestra mano (salvo por el efecto de una carta).

#### 2. Fase de fallo del sistema

Se descartan las dos primeras cartas del mazo de cartas de proyecto.

#### 3. Fase de activación del autómata

Tenemos que mirar el número de cartas en el Módulo de Preparación del autómata
para saber qué hace este turno.

* **Si tiene 0 ó 2 cartas de proyecto.** No hace nada

* **Si tiene 1 carta de proyecto.** Se mueve un colono de la nave del autómata
  (solo si tiene colonos) a la parte izquierda del edificio del mismo color que
  la carta que esté en el Módulo. Si no tiene colonos nueve 1 colono de la
  Tierra a su nave. Se activa el efecto específico para el autómata del
  Edificio:
  
  * **Edificio de Ecosistema:** el autómata gana dos promociones, a) se mueve 
    uno de sus colonos de la zona de la izquierda de cualquier edificio a la
    zona de la derecha, b) nos nueve uno de nuestros colonos de cualquier 
    edificio de la zona de la derecha a la zona de la izquierda. Tiene dos 
    promociones, por lo que esta acción se ejecuta dos veces y se da prioridad 
    a la opción *a)*.
  * **Edificio de Gestión de Agua:** descarta dos cartas del mazo de cartas de
    Proyecto. 
  * **Edificio de Energía:** la nave del autómata gana 2 de energía, si el
    nivel de energía está en el máximo se ejecuta la acción del Edificio de 
    Gestión de Agua. 
  * **Edificio de Ciencia:** si quedan colonos del autómata en la Tierra, mueve
    uno a su nave.
  * **Edificio de Construcción:** si el autómata no tiene colonos en su nave
    mueve uno de la Tierra a la nave. En caso contrario, mueve uno de los
    colonos de su nave a la zona izquierda de un Edificio. Hay que tratar de
    maximizar la puntuación del del autómata, por lo que se busca que tenga al
    menos 1 colono en cada Edificio y ganará puntos extra si tiene 4 colonos en
    el mismo Edificio (hablamos de esto más abajo en puntuaciones).
    

Después, si el Módulo del autómata no tiene 2 cartas, se roban tantas como sean
necesarias del mazo de cartas de Proyecto para dejar el Módulo del autómata con
2 cartas. Recordemos que si robando cartas no se puede llenar el Módulo del
autómata se termina la partida.


#### Cómo calcular las puntuaciones

Hay que calcular los Puntos de Victoria que hemos conseguido y los que ha conseguido el
autómata por separado:

**Nuestros puntos.** 
* 1 PV por cada colono en nuestra nave.
* 2 PV por cada colono en la zona de la izquierda de cada Edificio.
* 4 PV por cada colono en la zona de la derecha de cada Edificio.
* 1 PV si nuestra nave tiene un nivel de energía mayor o igual a la del
  autómata.
* 2 PV si tenemos al menos 1 colono en cada Edificio.
* 4 PV por cada 4 colonos en cada Edificio.
    
**Puntos del autómata.**
* *(igual)* 1 PV por cada colono en su nave.
* *(igual)* 2 PV por cada colono en la zona de la izquierda de cada Edificio.
* *(igual)* 4 PV por cada colono en la zona de la derecha de cada Edificio.
* **2 PV** si su nave tiene un nivel de energía mayor o igual a la nuestra.
* **4 PV** si tiene al menos 1 colono en cada Edificio.
* **5 PV** por cada 4 colonos en cada Edificio.



### Sobre el autómata del juego

Este autómata es algo especial ya que no se comporta siempre igual
independientemente de cómo estemos jugando, sino que nuestras acciones
repercuten en el autómata, y hasta cierto punto podemos *controlarlo*.

Pongo ese controlar en cursiva, porque no me estoy refiriendo a que tengamos
que jugar controlando a dos jugadores en bandos opuestos, sino que dentro de
nuestra estrategia de juego tenemos que tener en cuenta también qué va a
suceder con el autómata de jugar nuestro turno de cierta manera.
A mí esto es algo que me gusta, ya que a  diferencia de otros autómatas, por
ejemplo el de [Colonos del
Imperio]({{site.baseurl}}/2019/01/16/analisis-colonos-del-imperio/) del que os hablaba
hace unos meses, en el que el siempre se comporta igual, con el autómata de
Pocket Mars tenemos algo de interacción con este rival virtual ya que forma
parte de nuestra estrategia.

Además de tener en cuenta cómo y cuándo vamos a jugar cada carta, tenemos que
considerar si debemos jugar nuestras cartas, ya que el autómata se activaría
tras reponer nuestras 4 cartas, y en base a lo que tenga el autómata en el
Módulo, nos puede fastidiar más o menos. Podemos ignorar completamente el
autómata si queremos, y jugar a nuestro aire, pero no es la estrategia óptima.

El pequeño *control* que tenemos sobre las acciones del autómata en ocasiones 
puede llegar a que explotemos sus acciones a nuestro favor. Por ejemplo, si por
PVs ya vemos que vamos en cabeza y si el autómata tiene una carta de Gestión de
Agua en el Módulo, jugaremos la otra carta de su Módulo siempre, para ir 
agotando el mazo de cartas de Proyecto y forzar que el juego termine y así 
ganar. El autómata irá colocando colonos en ese Edificio, pero podemos calcular 
hasta qué punto nos interesa seguir esta estrategia.

Esta figura de un autómata que no es estático, sino que repercute activamente 
en nuestra estrategia de juego es algo que añade complejidad al juego y que yo
recibo de forma muy positiva.

Para añadir dificultad al juego el manual nos comenta que el autómata empiece
con 6 ó 7 colonos en la nave en vez de 5, a lo que yo adicionalmente añadiría
que, si el efecto del Edificio de Ciencia no puede activarse (movía un colono
de la Tierra a la nave del autómata) hagáis una tirada de 1d4 para activar
aleatoriamente el efecto de otro edificio.

### Opinión

**Apartado gráfico y componentes.**
Las ilustraciones de las cartas de Edificio y las naves de los jugadores me
gustan mucho, hace sonreír que los nombres de las naves estén sacados de series
de ciencia ficción de culto (Nostr o-mo, Nostromo de *Alien*; Rocinant-9,
Rocinante de *The Expanse*; Falcon 1K, el Halcón Milenario de *Star Wars* y
Enter / Prize, el Enterprise de *Star Trek*). Las
cartas de Proyecto me parece que están muy bien diseñadas también, ya que si
hubiesen utilizado ilustraciones en vez de diseños tipo esbozo las cartas 
podrían haber quedado algo recargadas. No entiendo porqué en los Edificios
ponen una estrella en la zona que vale 2PV y 2 estrellas en la zona que vale
4PV, es confuso.

Mención especial a una caja de tamaño justo para el juego, sin parafernalias
extra que no hacen más que quitar espacio.

**El juego.**
Sobre el juego en sí, creo que la propia descripción del juego en la caja le
hace bastante justicia "It's a heavy weight filler!". Un filler con bastante
peso, y creo que en solitario funciona mejor (no he jugado con más gente, pero 
he leído reseñas no en solitario de otras personas). Es un juego que
tiene bastantes decisiones, lo considero un juego con profundidad estratégica,
y en el que el autómata no solo empieza fuerte, sino que por como han sido
ponderadas los PVs va a tener siempre ventaja.
En cada partida, según toquen las cartas vas a poder usar una forma diferente 
de ganar, ya que hay combinaciones de efectos de cartas bastante variados.

Al igual que me pasaba en [Colonos del
Imperio]({{site.baseurl}}/2019/01/16/analisis-colonos-del-imperio/) me gustaría
que las partidas durasen más, pero como es tan fácil de preparar y ponerse a
jugar se soluciona sin problemas echando varias partidas seguidas.

En definitiva, es un juego en solitario muy recomendable y por ese precio
deberían quitárselos de las manos a los tenderos.

<img width="50" src="{{site.baseurl}}/favicon.ico"> **Puntuación:** 4 de 5
monedas. **¡Este juego es genial! Voy a jugar otra vez ya mismo.**

<hr>

[^1]: *Devious* puede traducirse como retorcido, tortuoso o enrevesado. A mí me
    gustaría que la compañía se hubiese traducido como *Autómatas Retorcidos*,
    por darle cierto toque malvado, pero desde 2Tomatoes lo han traducido como
    *Autómatas Astutos*.
