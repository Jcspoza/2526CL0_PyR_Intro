# CL0 - Presentación Taller PyR 2025 - 2026 +Demos

## Clase 0 - Indice - 90 minutos

- Requisitos de los alumnos/as
  
  - Necesarios
  
  - Deseables

- Presentación profesor – 10 minutos

- ¿Qué es la robótica?

- Enfoque: ¿Por qué Programación y Robotica simultáneamente? – 10 min

- Presentación alumnos -20 mins
  (Este es un taller personalizado para alumnos según sus intereses y formación previa => puesta en común)

- ¿Qué vamos a necesitar (minimo)?

- Demos

## Requisitos de los alumnos

Sintiéndolo mucho y para evitar que todos perdamos el tiempo, diré ante de nada, que el curso requiere unos requisitos mínimos por parte de los alumnos:

### **<u>Necesarios</u>**

#### 1- Familiaridad con los PC

Este taller requiere que tengas un manejo de un ordenador tipo PC de nivel medio, es decir debes ser capaz de:

- Escribir en programas en aplicación de editor de texto ( como un word, pero mas sencillo)

- Manejar ficheros del ordenador: copiar, mover , borrar, etc

- Navegar por la web, bajar ficheros etc.

- Conectar al puerto USB cables o pendrives y manejar los ficheros y programas dentro del pen

#### 2- Habilidades manipulativas manuales y cognitivas mínimas

Sintiéndolo mucho, si tienes **dificultades motoras serias con las manos**, este curso no es adecuado para ti.

Mismo caso, si tienes **deterioro cognitivo severo**.

Aceptamos sin problemas 'supuestos torpes' y no me importa repetir los conceptos si tu memoria no anda fina.

#### 3- No tener miedo a la electricidad a bajo voltaje

Manejaremos como máximo voltajes de 12 voltios y 1 amperio. La mayor parte del tiempo el voltaje será de 3,3 voltios o 5 voltios y la corriente del orden de decenas de miliamperios: es decir menos que inocuo 

#### 4- Inversión económica mínima

Vamos a trabajar con un microcontrolador llamado Pico W que no proporciona el centro, y tiene un coste de unos 12 euros. Además es necesario disponer de materiales electrónicos individuales, con un coste variable no superior a 50 euros. Este material más el microcontrolador se han comprado otros años como kits y sale mas económico.

También pueden ser necesarias algunas herramientas básicas como alicates o pelacables, o disponer de un multímetro básico. El profesor proporcionará de estas herramientas para las clases de cualquier forma

### <u>Deseables</u>

- Leer en ingles

- Haber programado con anterioridad (no importa el lenguaje)

- Manitas eléctrico

<u>**Si no crees cumplir alguno de los requisitos , te invito a quedarte para experimentar. decide si te quedas o no al final de la clase de hoy**</u>

---

## Presentación del profesor – 10 minutos

Currículo de Voluntario tecnológico del profesor [CV](./CV_JCSP_Voluntario_202510.pdf) 

## ¿Qué es la robótica?

Si  preguntáis a copilot (una IA)  diría: 

---

### 🤖 ¿Qué es la robótica?

La **robótica** es una rama de la ingeniería y la ciencia que se encarga del diseño, construcción, programación y uso de **robots**. Un robot es una máquina capaz de realizar tareas de manera automática, ya sea siguiendo instrucciones programadas o tomando decisiones por sí mismo mediante sensores e inteligencia artificial.

### 🧠 Disciplinas que combina

La robótica es un campo multidisciplinario que une varias áreas del conocimiento:

- **Ingeniería mecánica**: para construir la estructura y los mecanismos del robot.

- **Electrónica**: para controlar motores, sensores y circuitos.

- **Informática**: para programar el comportamiento del robot.

- **Inteligencia artificial**: para que el robot pueda aprender, adaptarse y tomar decisiones.

---

Yo diría que la robotica es la **ultima evolución del afán de los ser humanos por construir objetos útiles** (maquinas) **que le hagan la vida mas facil.**

La robotica **usa electricidad** tanto como **fuerza motriz** como para **comunicar informacion** entre los distintas componentes de un a maquina, como con el/los ser/es humano/s que la maneja/n

Concretando, la robotica usa:

- **sensores** (que leen informacion del mundo) 

- **actuadores** , como motores, luces calentadores etc que cambian el mundo circundandente

- dispositivos de **entrada y salida** para intercambiar informacion con los humanos, como teclados y pantallas

En todos estos dispositivos se aprovechan todos los avances de la física: electromagnetismo y cuántica principalmente, del siglo IXX al  XXI, junto con los desarrollos industriales derivados, por ejemplo el led ( las bombillas led) se basan en la física cuántica del principios del s XX y un desarrollo de ingeniería que abarco desde  el primer led en 1962, hasta el led azul de 1992 ( premio nobel 2014)

Si seguimos la definición más estándar de arriba, he de decir que **NO vamos a aprender ingeniería mecánica** en este curso de robótica. Tampoco creo que vaya a dar tiempo a aprender Inteligencia artificial. <u>Asi que nos vamos a centrar en : Electrónica e informática</u>

## Enfoque: ¿Por qué Programación y Robotica simultáneamente? – 10 min

La frontera es difusa, hay diferencias al comienzo del aprendizaje de Programación o
Robotica, que luego cuando se avanza se reducen. Lo ideal sería aprender tanto
Programación como Robótica.

| PROGRAMACION                                                                                                                                                  | ROBÓTICA                                                                                                            |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Mas Abstracto, los programas se ejecutan en un ordenador y no interactúan con el mundo salvo el teclado y la pantalla (hasta que se hacen cosas con internet) | Mos concreto, se pueden hacer "cacharros" como termostatos, estaciones meteorológicas, etc                          |
| Rápidamente se avanza a programas más complejos y más “inteligentes”                                                                                          | Los programas que se cargan en el microcontrolador son relativamente simples, aunque poco a poco se van complicando |
| No se necesita hardware para empezar (microcontrolador y materiales de robótica), salvo un PC o similar                                                       | Se NECESITA hardware para empezar: materiales de robótica y microcontrolador                                        |

En <u>programación</u>, **Python** es sin duda el lenguaje mas adecuado para aprender (en edad adulta) porque es :

- **Gratis** (al igual que su código fuente y sus bibliotecas).

- **Fácil de aprender y de usar**. Beneficia tanto a los principiantes como a los expertos.

- **Sintaxis legible**.

- **Libre** y de **código abierto** (open source).

- Amplias **bibliotecas**.

- **Creación rápida** de programas: ***es un lenguaje Interpretado***

- **Extensible e integrable** con otros lenguajes

- Funciona en los principales sistemas operativos y plataformas informáticas

Mas razones en los siguientes videos

[Video corto en castellano 1 ](https://www.tiktok.com/@edteam/video/7410916311821323526?is_from_webapp=1&web_id=7343715684931307040)

[Video corto en castellano 2](https://www.tiktok.com/@edteam/video/7410916311821323526?is_from_webapp=1&web_id=7343715684931307040)

[3 Reasons to Learn Python - AI and LLMs is One of Them, but There are MORE!](https://www.youtube.com/watch?v=EHsLuHbE_9s)

En <u>Robotica</u>, hasta hace poco tiempo había que usar para programar los microcontroladores, que son el cerebro de los proyectos de robotica, lenguajes relativamente oscuros como "C" o derivadas de C ( IDE Arduino) . Afortunadamente, en 2013 el físico Australiano Damien George, desarrollo junto a otros personas **micropython** para el microcontrolador PyBoard, y rápidamente se ex- "porto" a otros microcontroladores como ESP32 o **RPI Pico, que es el que usaremos**

**Micropython** es una implementación del lenguaje de programación Python 3, escrita en C, optimizada para poder ejecutarse en un microcontrolador. Es decir **permite programar los microcontroladores con "programas" escritos en un sub-conjunto de Python con alguna peculiaridad del microcontrolador** por lo que son aplicables todas las ventajas de Python

***En este curso se aprende simultáneamente Python y microPython con lo cual el aprendizaje se realimenta y multiplica***

## Presentación alumnos -20 mins

Es el momento de conocernos un poco, porque este es un taller personalizado para alumnos según sus intereses y formación previa 

--> Hagamos una puesta en común de 20 mins

## ¿Qué herramientas vamos a necesitar (minimo)?

*Herramientas SW* : <u>**IDE:**</u> Para programar **tanto en Python como en micropython** vamos usar **<u>Thonny</u>** que es un IDE: Entorno integrado de Desarrollo. Es gratis y solo necesitamos instalarlo en un PC o en un pendrive : lo contaremos en la clase 1.

*Herramientas HW*: **<u>Microcontrolador</u>**: ya hemso comentado que es como el cerebro de todos los proyectos de robotica, es también donde se conectan todos los sensores, displays, etc. El **año pasado decidimos usar el microcontrolador <u>Raspberry Pi Pico W</u>** 

Seguiremos con él el curso 2024 - 2025, porque las razones no han cambiado y el precio es aproximadamente el mismo. Comentaremos este tema en próximas clases

**Novedad:** Recientemente, agosto 2024, ha aparecido una versión muy mejorada de la Raspberry Pico -> [**Raspberry Pi Pico 2**: A Powerful New Addition to the Microcontroller Family | Elektor Magazine](https://www.elektormagazine.com/news/raspberry-pi-pico-2-a-powerful-new-addition-to-the-microcontroller-family)) muy interesante, pero de momento sin wifi asi que nos quedaremos con el Pico W

Lo ideal es comprar un kit, pero se puede empezar solo con el microcontrolador + una Protoboard y algunas cosas (muy baratas) mas.

---

## Demos

### Demo de Robotica : Tira Led (x8) de colores controlada por display, pulsadores y botón rotativo

He preparado sobre un montaje con el que acabamos el curso anterior de un 'display' mas 3 pulsadores y botón de rueda . he añadido una tira neopixel de ledes de colores controlables individualmente ( también vista el curso pasado)

[Tira 8 led de colores y control con display](./Rdemo_neopx8_showMenu_2_0.py)

### Demo de Programación : Juego 'Mata-puntos'

Es del curso 2023 a 2024, incluye programación grafica ( sencilla) . es un juego qu epodria servir para evaluar las habilidades de manejo del ratón de ordenador : 

    Se trata simplemente de clicar en los puntos rojos ( bastante grandes) que aparecen en pantalla, y que van aumentando su velocidad de aparición, hasta ver cuantos puedes 'matar'

[Juego Mata puntos](./Pdemo_MataPuntos_GZch7_2_0.py)

## Tabla resumen de programas

| Programa                                                                      | Lenguaje                    | HW si Robotica y Notas                                  | Objetivo de Aprendizaje   |
| ----------------------------------------------------------------------------- | --------------------------- | ------------------------------------------------------- | ------------------------- |
| [Tira 8 led de colores y control con display](./Rdemo_neopx8_showMenu_2_0.py) | micropython (uPython, o uP) | GPIO16 -> R220 ohm -> LED1 cátodo  y R220 -> LED2 ánodo | Programa demo de robotica |
| [Juego Mata puntos](./Pdemo_MataPuntos_GZch7_2_0.py)                          | Python                      | Input()no funciona con algunos IDE python on line       | Programa demo de  Python  |

---

TO DO :
