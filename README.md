# Modelo de Regresión para la predicción del nivel de glucosa

Este repositorio contiene una notebook de Google Colab que desarrolla un modelo de regresión para predecir el nivel de glucosa utilizando un conjunto de datos de características clínicas.

## Descripción

El objetivo de este proyecto es construir y evaluar un modelo de regresión que pueda predecir el nivel de glucosa de una persona, basándose en ciertos factores clínicos y demográficos. La notebook incluye los pasos de preprocesamiento de datos, selección de características, entrenamiento del modelo y evaluación de su rendimiento.

## Contenido del Repositorio

- `Modelo_Regresion.ipynb`: La notebook principal que contiene todo el flujo de trabajo del proyecto, desde la carga de datos hasta la evaluación del modelo.
- `Hipertension_Arterial_Mexico.csv`: El archivo de datos que contiene la información médica y demográfica de los pacientes.
- `hipertensin-arterial-mxico-metadata.json`: Archivo JSON que contiene metadatos detallados sobre el conjunto de datos.

## Datos

El conjunto de datos utilizado en este proyecto proviene del [Hipertension Arterial Mexico Data Set]([https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset/versions/1](https://www.kaggle.com/datasets/frederickfelix/hipertensin-arterial-mxico/versions/4)) en Kaggle. El archivo de datos `Hipertension_Arterial_Mexico.csv` contiene datos médicos y demográficos de los pacientes, junto con su riesgo de hipertensión (en riesgo o no en riesgo). Las características incluyen edad, género, concentración de hemoglobina, temperatura ambiente, niveles de ácido úrico, albúmina, colesterol (HDL, LDL, total), creatinina, glucosa, insulina, proteína C reactiva, triglicéridos, glucosa promedio, hemoglobina glucosilada, ferritina, folato, homocisteína, transferrina, vitamina B12, vitamina D, peso, estatura y circunferencia de la cintura, entre otros.

### Metadatos del Dataset

El archivo `hipertensin-arterial-mxico-metadata.json` contiene información detallada sobre las características del conjunto de datos, incluyendo los tipos de datos, descripciones de las columnas y otra información relevante para entender mejor los datos.
