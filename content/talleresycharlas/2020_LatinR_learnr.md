---
title: Taller de {learnr}
authors:
- "paocorrales"
date: 2020-10-05T21:13:14-05:00
tags:
  - RMarkdown
  - Taller
  - learnr
  - LatinR
---

Este año LatinR se lleva a cabo de mantera virtual, y si bien se extraña el encuentro de toda la comunidad, al mismo tiempo nos da la posibilidad de encontrarnos con personas que tal vez no pueden viajar. 

Entre otras cosas, se dictaron muchos talleres y capítulos de RLadies y Grupos de usuarios de R se ofrecieron a organizar. Con [Yanina Bellini](https://twitter.com/yabellini) dimos el taller de {learnr} para generar tutoriales interactivos con la organización de [RLadies Santa Rosa](https://www.meetup.com/es-ES/rladies-santa-rosa/) y [RLadies General Pico](https://www.meetup.com/es-ES/rladies-general-pico) (gracias!). Este taller es parte de los talleres y materiales que generamos en [MetaDocencia](https://metadocencia.org/), una comunidad de docentes que busca desarrollar y aplicar métodos de enseñanza concretos, basados en evidencia y centrados en tus estudiantes.

En este post les comparto los materiales que usamos, con suerte les serán útiles.

- [Presentación](https://docs.google.com/presentation/d/1QLRUbERgEk85s8qK6mzmMJn7avQ_bEmTn_NzFYgqwkc/edit)
- [Infinitos recursos para explorar](https://github.com/yabellini/curso_learnr)
- [Un tutorial de prueba](https://paocorrales.shinyapps.io/R-meteo/)
- Video? Muy pronto!

Además una de las cosas que charlamos durante el taller fue como traducir la estructura del tutorial al español, por ahora aparecen botones que dicen "Hint" o "Run code" que no son muy amigables para todo el mundo. Lamentablemente todo eso está definido en un archivo de Java que corre y general esa estructura. Si bien [existe la posibilidad de modificar ese archivo](https://gist.github.com/eliocamp/b2b82f9c3c622964696c5b308c9ae108), al hacerlo estamos cambiando la instalación misma del paquete {learnr} haciendo que nada de lo que hagamos sea reproducible o modificando la instalación de otras personas al hacerlo!

La buena noticia es que [hay personas trabajando en eso](https://github.com/rstudio/learnr/issues/388#issuecomment-703287714), y con suerte habrá novedades en el futuro. 
