# Proyecto de Machine Learning para la Predicción y Clasificación de Precios de automoviles

Este repositorio contiene un proyecto de Machine Learning que se enfoca en desarrollar modelos para predecir el precio de los automoviles y clasificarlos como baratos o caros basados en la mediana, utilizando un dataset de datos de automoviles. El proyecto está diseñado para brindar ejemplos de cómo construir tanto un modelo de regresión predictiva como un modelo de clasificación en el contexto automotriz.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto contiene información detallada sobre diferentes automoviles, incluyendo características como el tamaño del motor, la potencia, el consumo de combustible en ciudad y carretera, entre otros. El archivo de datos se encuentra en `data/ML_cars.csv` y está en formato CSV.

Cabe destacar el reducido tamaño del dataset, esto se debe a que este projecto esta basado en material brindado por un bootcamp.

## Contenido del Repositorio

El repositorio está organizado de la siguiente manera:

- `data/ML_cars.csv`: El conjunto de datos en formato CSV que contiene la información de los automoviles.
- `notebooks/modelos.ipynb`: Un notebook de Jupyter que demuestra el proceso de construcción de un modelo de regresión para predecir el precio de los automoviles. Y cómo desarrollar un modelo de clasificación para categorizar los automoviles como baratos o caros.
- `README.md`: Este archivo README que proporciona información relevante sobre el proyecto.

## Notebooks

### Predicción del Precio de automoviles y Clasificación de automoviles Baratos y Caros

En el notebook `modelos.ipynb`, se realiza un análisis exploratorio de los datos, seguido por la construcción de un modelo de regresión para predecir el precio de los automoviles en función de sus características. Se utilizan técnicas de preprocesamiento, selección de características y evaluación del modelo para lograr un rendimiento óptimo.

Y ademas se lleva a cabo un proceso de un problema de clasificación. Se exploran las características relevantes, se dividen los datos en conjuntos de entrenamiento y prueba, y se entrena un modelo de clasificación para determinar si un vehículo es barato o caro en función de la mediana de los precios.

## Requisitos

Para ejecutar los notebooks, se requiere tener instalado Python junto con las siguientes bibliotecas:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter
- XGBoost

Se recomienda configurar un entorno virtual antes de instalar estas bibliotecas.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local.
2. Abre los notebooks en Jupyter Notebook o Jupyter Lab.
3. Ejecuta las celdas de los notebooks en orden para ver los pasos realizados en el análisis y la construcción de los modelos.

¡Disfruta explorando y construyendo modelos de Machine Learning para predecir y clasificar precios de automoviles! Siéntete libre de modificar y mejorar el código según tus necesidades.
Y de retornar cualquier retroalimentacion sobre el proyecto.

Tobias Sirne..
