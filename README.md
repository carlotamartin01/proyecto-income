# Proyecto de clasificación de ingresos

Este proyecto consiste en clasificar si una persona gana más o menos de 50K al año usando el dataset income_data.csv. He trabajado todo en notebooks y he seguido un proceso completo: análisis exploratorio, preprocesado, modelos y evaluación.

## Estructura

- data/: datos originales y procesados
- src/: notebooks del EDA, preprocesado, modelos y test final
- docs/: documento con instrucciones del trabajo

## Modelos usados

- Random Forest
- LightGBM (es el mejor)
- Red neuronal (probada pero descartada y eliminada ya que necesitaba escalar y tampoco daba el mejor resultado)

He ajustado hiperparámetros, dividido bien el dataset en train, validación y test, y aplicado todo lo necesario para que el modelo sea estable y sin sobreajuste.

## Resultados finales en test (LightGBM)

- Accuracy: 0.871
- Precision: 0.776
- Recall: 0.650
- F1: 0.707
- ROC AUC: 0.924

## Librerías usadas

- pandas, numpy, matplotlib, seaborn
- scikit-learn
- lightgbm

