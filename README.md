# ToxicDetection

Este repositorio contiene la solución al problema Toxic Detection propuesta por César Garrido Urbano como prueba técnica para Mercado Libre.


## Descripción

El objetivo es construir un sistema para detectar automáticamente textos que contienen lenguaje ofensivo (inclusive de género, raza, etc...) o vulgar.

Para esto debes generar un modelo de clasificación utilizando un esquema basado en árboles de decisión. (Por ejemplo: Random Forest, XGBoost, LightGBM, etc...).

El proceso de desarrollo debe seguir el flujo completo de modelado en _Machine Learning_ (análisis de datos, feature engineering, selección de modelo, métricas) con reporte de resultados y proceso. Toda decisión tomada dentro del pipeline debe ser agregada al reporte.

Luego de haber seleccionado el mejor modelo de clasificación, para el reporte, haz un análisis comparativo de los dos mejores modelos que hayas obtenido con la métrica que consideres se adapta mejor al problema.

## Datos
El dataset está incluido en este folder bajo el nombre data_toxic.csv.

A continuación, una descripción de las columnas:


| Variable              | Descripción                                                  |
|:----------------------|:-------------------------------------------------------------|
| message               | Texto en español                                             |
| label                 | 1 para mensaje tóxico y 0 para no tóxico                     |

## Contenido

En este repositorio encontrara un jupyter notebook con la solución construida para este problema siguiendo el flujo completo de modelado en *Machine Learning*
