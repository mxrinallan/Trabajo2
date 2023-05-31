---
title: "Segunda Tarea"
author: "Allan Marín"
format: html
editor: visual
---


## Graficación sobre la calidad del café según el Instituto de calidad del café (CQI)

### Grupo 002

#### Introducción

Este docummento presenta datos relacionados con la calidad del café, en el cual se utiliza el lenguaje de programación R, visto en clase, el cual crea tablas y graficos de gran ayuda para el entendimiento del tema a desarrollar. 

Para este trabajo, utilizaremos un conjunto de datos suministrados por el [Coffee Quality Institute (CQI)](https://github.com/fatih-boyar/coffee-quality-data-CQI), los cuales fueron tomados desde el siguiente enlace https://github.com/fatih-boyar/coffee-quality-data-CQI. Este repositorio incluye muestras de café de diferentes partes del mundo. Estos datos contienen información detallada sobre el país de origen, la altitud, la variedad, el color y el método de procesamiento del café, así como las evaluaciones de diversas características, como aroma, sabor, acidez y puntaje total.

Nuestra meta para este proyecto es utilizar los conocimientos adquiridos en clase y los datos necesarios para realizar graficos y tablas los cuales muestren el analisis de los datos que nos ayuden a comprender mejor los factores que influyen en la calidad del café.

## Carga de paquetes de R

```{r}
#| label: Carga-datos
#| warning: false
library(DT)
library(ggplot2)
library(plotly)
library(dplyr)
library(tidyverse)
library(ggthemes)
library(readr)
```

## Carga de datos

```{r}
read_csv("C:/Users/marin/Downloads/TAREA2_Procesamiento/coffee-quality.csv")
```
