
# ☀️ Solar Production Forecasting - Nouvelle-Aquitaine (FRANCE)
(English) -> A Full Data Analysis &amp; using (1.) weather data, (2.) solar irradiance data, and (3.) the solar production from the centrals in this french region.

(Spanish) -> Este proyecto usa Machine Learning (modelos XGBoost y Random Forest). El objetivo es predecir la producción de energía solar basándose en datos meteorológicos, datos de irradiancia solar, y la producción solar pasada en este región de Francia.

## PROJECT SLIDES
* [Ver Diapositivas del Proyecto](slides)

## Execution
Puedes ejecutar el modelo directamente en Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](definitive_productions.ipynb)

## Desafíos Superados
1. **Data Leakage:** Eliminación de variables futuras para un modelo real "Day-Ahead".
2. **Model Bias:** Superamos la regresión a la media del Random Forest mediante XGBoost.
3. **Robustez:** nMAE diurno estabilizado en un **4.62%**.

## Resultados
- **MAE Diurno:** 99.58 MW
- **Modelo** con error máximo de 200MW, y media en torno a 100MW.
