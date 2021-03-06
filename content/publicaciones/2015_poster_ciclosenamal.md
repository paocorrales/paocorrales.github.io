---
title: "Análisis del ciclo semanal en el Rango de Temperatura Diaria para Sudamerica"
authors: 
- "paocorrales"
date: 2015-03-22T21:13:14-05:00
tags:
  - poster
  - datos
  - R
  - meteorología
---

En 2014 casi de casualidad descrubrí los cursos de Data Science de la Universidad Johns Hopkins en [Coursera](https://www.coursera.org/specializations/jhu-data-science) y con esos cursos mi primer acercamiento a R. En la misma época con Elio Campitelli empezamos a pensar en un trabajo para presentar en el CONGREMET XII (el único congreso de meteorología en Argentina) para no ir con las manos vacías. 

Y así, sabiendo muy poquito de R analizamos una base de datos de estaciones meteorológicas en Argentina y paises limítrofes con la intención de buscar una relación entre el rango de temperatura (la temperatura máxima menos la temperatura mínima) y los días de la semana. Aprendimos muchísimo.

Pueden ver el poster que presentamos [acá](https://www.dropbox.com/s/s90g5m3ky3vqwfq/AN%C3%81LISIS%20DEL%20CICLO%20SEMANAL%20EN%20EL%20RANGO%20DE%20TEMPERATURA%20DIARIA%20EN%20SUDAM%C3%89RICA_poster.pdf?dl=0), [acá](https://www.dropbox.com/s/d0nip1jyv82ql0l/AN%C3%81LISIS%20DEL%20CICLO%20SEMANAL%20EN%20EL%20RANGO%20DE%20TEMPERATURA%20DIARIA%20EN%20SUDAM%C3%89RICA.pdf?dl=0) el trabajo completo o pueden leer el resumen abajo.

## Resumen

El ciclo semanal refiere a la variación de una variable meteorológica causada por diferencia en la actividad humana entre los días hábiles y los fines de semana. Aunque fue observado en diversas regiones del planeta, no existe evidencia inequívoca de su existencia. Este es el primer trabajo que investiga el fenómeno en Sudamérica. Se buscó un ciclo semanal en el rango de temperatura diario
(DTR) durante el período 1991-2005 para 81 estaciones en Argentina y Paraguay usando dos métodos distintos. Por un lado se ajustó un modelo sinusoidal con período de 7 días y se evaluó la significancia estadística de su amplitud mediante un análisis de Monte Carlo. Por el otro se comparó el ciclo de una semana usual con los correspondientes a una semana de 6 u 8 días. Se encontró un ciclo de 7 días estadísticamente significativo para Paraguay y el norte y litoral argentinos pero también se encontró un ciclo de 8 días más marcado en las mismas regiones. Los resultados no fueron concluyentes y ameritan un estudio más amplio y detallado.