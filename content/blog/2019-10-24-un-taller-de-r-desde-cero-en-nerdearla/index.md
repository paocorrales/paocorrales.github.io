---
title: Un taller de R desde cero en nerdearla
author: Pao Corrales
date: '2019-10-24'
slug: []
categories:
  - Español
  - workshop
tags:
  - R
  - RLadies
---

Hace un par de días tuve la super gran oportunidad de probar algunas prácticas que fui descubriendo en los últimos meses gracias a los materiales de The Carpentries y el workshop de  Mine Çetinkaya-Rundel en LatinR. 

### ¿Dónde? 

Todos los años se organiza el evento [NERDEARLA](https://twitter.com/nerdearla), una mezcla de charlas, tallares y networking. Y este año desde RLadies Buenos Aires aceptamos la invitación de participar con un taller de R para principiantes. Y ahí fuimos con Flor, Priscila, Moni, Betsy, Kari y Jesi con mucha curiosidad sobre lo que nos íbamos a encontrar. En resumen, estuve genial. Participaron muchísimas personas (más de 60!) en un ambiente super amigable y lleno de preguntas. 

### El taller

Al presentar la propuesta para el taller me puse dos objetivos:

1- Que fuera orientado específicamente a análisis de datos jugando con datos reales en vez de ver programación básica.
2- Enseñar algunas buenas prácticas desde el principio como usar proyectos y RMarkdowns para informes. 

En la práctica eso derivó en focalizar el taller en aprender algunas cosas básicas de dplyr y de ggplot2 en conjunto con el uso de RStudio, pipes y RMarkdowns (pero sin entrar en detalles escabrosos). Tratando de aplicar la idea de ["Let them eat cake (first)"](https://speakerdeck.com/minecr/let-them-eat-cake-first-0a3bbf75-f6f1-42d5-8d2f-ac2ff741611f) la base para trabajar con estos paquetes fueron pequeños reportes de RMardown (casi) completos a los que le fuimos haciendo cambios pequeños para entender (casi todas) las líneas de código. 

### Los datos

Prometimos datos reales así que mi fuente de inspiración fue #tidytuesday y #datosdemiercoles y después de revisar un poco me quedé con esta base de datos de meteoritos. Si bien creo que el mayor jugo requiere análisis más complejos de los que hicimos, estos datos tienen cierta simpleza y general (creo) curiosidad. Además tenía ganas de usarlos!

Los ejercicios. A simple vista los ejercicios son muy simples: "Buscá la línea de código que filtra los datos para quedarnos con los meteoritos encontrados y cambiala para contar los meteriotos que fueron vistos caer". Esto es cambiar "Found" por "Fell" dentro de la función `filter()`, pero al mismo tiempo permite charlar de otras cosas:

- Qué está haciendo la función filter?
- R interpreta igual "Fell" y "fell"?

### Los materiales

Durante el taller mostramos una presentación y usamos un proyecto en RStudio Cloud

* [Slides](https://docs.google.com/presentation/d/1rYRcGhlLRM4fCr6-CxX060y7W2HBJ2bY-Nk1SgFQZtw/edit#slide=id.g435a0b21f9_1_18)
* [Proyecto](https://rstudio.cloud/project/616243)