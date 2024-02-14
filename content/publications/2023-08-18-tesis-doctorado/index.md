---
title: Utilización de datos satelitales para la evaluación y mejora de los pronósticos numéricos en alta resolución a muy corto plazo
author: Paola Corrales
date: '2023-08-18'
slug: tesis-doctorado
categories:
  - Academic
  - meteorology
  - Español
tags: []
Links:
- icon: github
  icon_pack: fas
  name: Repo
  url: https://github.com/paocorrales/Tesis_doctorado
- icon: door-open
  icon_pack: fas
  name: Web
  url: https://paocorrales.github.io/Tesis_doctorado
- icon: database
  icon_pack: fas
  name: Datos
  url: https://zenodo.org/record/7968629
---

Luego de casi 6 años de trabajo, me doctoré! La tesis en cuestión está escrita usando RMarkdown y thesisdown para generar al mismo tiempo un hermoso pdf con el formato que requiere la universidad y una [web abierta](https://paocorrales.github.io/Tesis_doctorado/Tesis_doctorado) y disponible para todo el mundo. 

**Resumen** En la Argentina, los fenómenos meteorológicos extremos producen cuantiosas pérdidas humanas y materiales. Muchos de estos fenómenos, por ejemplo tornados, ráfagas intensas, precipitaciones extremas en cortos períodos de tiempo, granizo de gran tamaño y actividad eléctrica, están asociados a la ocurrencia de convección profunda. Es por tal motivo necesario avanzar en el conocimiento de estos fenómenos y en la capacidad de pronosticar la ocurrencia de los mismos. El pronóstico de los fenómenos severos es un desafío científico y tecnológico muy complejo debido a la predictibilidad limitada en la mesoescala y a la dificultad de conocer o diagnosticar el estado de la atmósfera en escalas espaciales pequeñas y tiempos cortos (por ejemplo de 1 a 10 km y del orden de los minutos). La asimilación de datos en la mesoescala es un enfoque que puede proporcionar condiciones iniciales adecuadas para generar pronósticos numéricos de alta resolución y, por tanto, es un área de estudio en constante evolución.

Para que los métodos de asimilación de datos tengan éxito, deben utilizarse redes de observación con suficiente resolución temporal y espacial capaces de captar la variabilidad de la mesoescala. La relativa escasez de observaciones convencionales en Sudamérica supone un importante desafío que puede ser resuelto con el uso de otras fuentes de observaciones como estaciones de superficie automáticas, vientos derivados de observaciones satelitales y radianzas de satélites polares y geoestacionarios en cielo despejado. En este contexto, este trabajo de tesis busca cuantificar y comparar el impacto de cada uno de los conjuntos de datos en un sistema de asimilación de mesoescala.

El estudio de la asimilación de radianzas a nivel regional, en primera instancia para cielos despejados, cobra aún mayor importancia en Sudamérica ya que no se conocen estudios realizados previamente y la red de observaciones convencionales tiene baja resolución espacial. Por esta razón, en este trabajo se hace especial énfasis en la asimilación directa de radianzas y los controles de calidad necesarios para trabajar con estas observaciones. En primer lugar se estudia el impacto de la asimilación de observaciones de satélites polares con sensores sensibles al espectro infrarrojo y microondas. Y en segundo lugar, se estudia la implementación de la asimilación de observaciones del satélite geoestacionario GOES-16 y el impacto de asimilar observaciones en alta resolución espacial y temporal en un contexto regional.

Para alcanzar los objetivos de esta tesis, se realizaron distintos experimentos de asimilación de datos aplicados a un estudio de caso de un sistema convectivo de mesoescala que se desarrolló sobre el sur de Sudamérica durante el 22 y 23 de noviembre de 2018 durante el período de observación intensiva de la campaña de campo RELAMPAGO. Se utilizó el sistema WRF-GSI-LETFK para la generación de los experimentos de actualización frecuente y basados en ensambles. Mientras que el modelo WRF es uno de los más utilizados y en constante avance, con importantes antecedentes en Argentina, el sistema de asimilación GSI y en particular su versión de LETKF, no ha sido probado en Argentina y es uno de los aportes originales de esta tesis.

Los resultados obtenidos muestran que la asimilación de observaciones con alta frecuencia temporal y espacial genera un importante impacto en la capa límite planetaria corrigiendo el bias cálido y seco presente en el modelo generando un mejor desarrollo de la convección profunda y la precipitación para el caso de estudio. La asimilación de las observaciones de radianza produjo un mejor desarrollo de la convección conduciendo a un aumento de la precipitación acumulada. El pronóstico por ensambles inicializado a partir de cada experimento también mostró mejoras en la representación de la precipitación. Finalmente la implementación de la asimilación de observaciones de GOES-16 mostró ser adecuada produciendo pronósticos de precipitación más cercanos a lo observado. En particular los experimentos de sensibilidad generados para analizar el impacto de asimilar observaciones de los tres canales de vapor de agua mostraron que el canal 10, asociado al contenido de vapor de agua en niveles bajos, aporta casi tanta información como asimilar simultáneamente los 3 canales de vapor de agua, particularmente cuando las observaciones son asimiladas utilizando una resolución espacial similar a la del modelo (10 km).
