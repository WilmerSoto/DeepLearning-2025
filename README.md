# Análisis y Predicción de Patrones en Caídas de Meteoritos

## Autor
Wilmer Santiago Soto Vidal

## Descripción General del Proyecto
Este proyecto de Machine Learning explora el dataset de Meteorite Landings de la NASA[cite: 1]. El objetivo principal es analizar y predecir patrones relacionados con las caídas y hallazgos de meteoritos, centrándose tanto en su distribución espacial (dónde) como en su frecuencia a lo largo del tiempo (cuándo).

El análisis busca ofrecer perspectivas sobre las características de los meteoritos registrados y desarrollar modelos predictivos para identificar zonas de interés potencial y comprender las tendencias históricas.

Para un detalle completo sobre el contexto, objetivos específicos, descripción a fondo del dataset, metodología y métricas, consulte el documento [ENTREGA1.pdf](https://github.com/WilmerSoto/DeepLearning-2025/blob/main/ENTREGA1.pdf) incluido en este repositorio.

## Dataset
* **Nombre:** Meteorite Landings
* **Fuente:** NASA (vía Kaggle)
* **Enlace:** https://www.kaggle.com/datasets/nasa/meteorite-landings
* **Tamaño:** 45,716 registros, 10 columnas. Peso del archivo .csv: 4.21 MB.
* **Contenido Clave:** Información sobre nombre, masa, ubicación (lat/long), año, tipo de hallazgo (caído u encontrado) y clasificación de los meteoritos.

## Objetivos de Predicción (Resumen)
El proyecto aborda la predicción desde dos perspectivas principales:

1.  **Predicción Espacial:** Predecir la probabilidad o el número esperado de caídas/hallazgos por región, utilizando enfoques de clasificación (riesgo Alto/Bajo) y regresión (conteo/densidad).
2.  **Predicción Temporal:** Predecir la frecuencia (número) de caídas de meteoritos en futuros períodos de tiempo basándose en tendencias históricas.

## Métricas de Desempeño
Se evalúan los modelos utilizando métricas tanto técnicas de Machine Learning como métricas que reflejan el valor científico o de aplicación del proyecto.

* **Métricas de Machine Learning:** Se usarán métricas estándar según el tipo de predicción (ROC AUC, F1-Score, Matriz de Confusión para clasificación; MAE, RMSE, SMAPE para regresión y series temporales).
* **Métricas de Valor Científico / Aplicación:** Se enfocan en la utilidad de las predicciones, como el potencial para optimizar la búsqueda de meteoritos, la fiabilidad de la previsión global de caídas, y la identificación de patrones o factores predictivos relevantes.

## Estructura del Repositorio
WIP
