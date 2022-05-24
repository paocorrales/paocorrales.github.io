---
title: SISINTAR
date: 2022-03-01
excerpt: "Paquete de R para procesar y acceder a los datos de SISINTA"
author: "Pao Corrales"
featured: true
draft: false
layout: single
tags:
  - R
categories:
  - R packages
  - Español
  - R
links:
- icon: github
  icon_pack: fab
  name: repo
  link: https://github.com/INTA-Suelos/SISINTAR
- icon: door-open
  icon_pack: fas
  name: Website
  url: https://sisinta.shinyapps.io/sisintar-web/
---

El paquete `{SISINTAR}` incluye una serie de funciones para acceder y procesar los datos dispobibles en [SISINTA](http://sisinta.inta.gob.ar/). Por ejemplo, la función `buscar_perfiles()` permite buscar perfiles en función de la localización, la fecha y la clase o, si se corre sin argumentos, devolver la lista de perfiles completa. Para descargar lo datos de los perfiles se usa la función `get_perfiles()`. Ésta toma un vector con los ids de los perfiles a descargar.

La documentación del paquete está escrita 100% en español, pensando en les usuaries destino, como así también la viñeta que lo acompaña.  

En conjunto se desarrolló una herramienta web para exportación de datos de SISINTA: 

[sisinta.shinyapps.io/sisintar-web/](https://sisinta.shinyapps.io/sisintar-web/)

Esta aplicación permite la descarga de perfiles de suelo disponibles en la base de datos SiSINTA. Es posible buscar y seleccionar perfiles de acuerdo a un área geográfica (ingresando coordenadas o dibujando un polígono) y/o por fecha.

Previo a la exportación de los datos (en formato CSV o EXCEL) se pueden selecionar variables específicas y procesarlas para obtener datos en horizontes específicos.


