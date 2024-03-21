---
title: agroclimatico
date: 2021-03-01
excerpt: "Conjunto de funciones para calcular índices y estadísticos climáticos hidrológicos a partir de datos tidy. Incluye una función para graficar resultados georeferenciados y e información cartográfica."
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
  link: https://github.com/AgRoMeteorologiaINTA/agroclimatico
---

*Update! Now `agromet` is `agroclimatico`*

El paquete `{agromet}` incluye una serie de funciones para calcular índices y estadísticos climáticos e hidrológicos a partir de datos tidy. Por ejemplo `umbrales()` permite contar la cantidad de observaciones que cumplen una determinada condición y `dias_promedios()` devuelve el primer y último día del año promedio de ocurrencia de un evento.

Otras funciones como `spi()` funcionan como wrappers de funciones de otros paquetes y que buscan ser compatibles con el manejo de datos tidy.

Finalmente el paquete incluye una función de graficado de datos georeferenciados `mapear()` con el estilo y logo propios de INTA.

La documentación del paquete está escrita 100% en español, pensando en les usuaries destino, como así también la viñeta que lo acompaña.  
