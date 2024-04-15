## Contaminación atmosférica por NO2 ##  

![imagen](aq_image.jpeg)  

Este repositorio contiene un análisis y desarrollo de modelos de machine learning para predecir la contaminación de NO2 en la atmósfera en función de otros elementos contaminantes, la temperatura y la humedad. A continuación, se detalla el contenido y los pasos realizados:


***Contenido del Repositorio:*** 

AirQuality.csv: archivo CSV que contiene el DataSet original del proyecto. Se encuentra en la ruta: src/data/original_file  

air_quality.csv: archivo CSV que contiene el DataSet ya limpio, es decir, una vez ya efectuada la limpieza de los datos posterior al análisis exploratorio. Se encuentra en la ruta: src/data/cleaned_file

**Analysis_and_Cleaning.ipynb**  
Notebook que contiene el código de Python para el análisis exploratorio y la limpieza de los datos.  

**Machine_Learning_Model.ipynb**  
Notebook que contiene el código de Python para el preprocesamiento, la construcción y evaluación de modelos de machine learning. 

**model**: modelo final entrenado y guardado utilizando el mejor clasificador según los resultados obtenidos.  

***Pasos Realizados en los Notebooks:***  

- Lectura de los datos desde el archivo AirQuality.csv
- Observación de la distribución de la variable objetivo o target (NO2(GT)).
- Análisis de la correlación entre las variables.  
- Aplicación de la transformación logarítmica para normalizar la distribución de los  debido a la presencia de valores extremos (outliers).
- Estandarización y escalado de las variables numéricas.
- Generación de clases "baja", "moderada" y "alta" de la concentración de NO2.
- Evaluación de varios modelos de clasificación, incluyendo Regresión Logística, Random Forest, AdaBoost, Árbol de Decisión, Support Vector Machine (SVM,) K-Nearest Neighbors (KNN), Redes Neuronales, entre otros.
- Optimización de hiperparámetros mediante búsqueda de cuadrícula (GridSearchCV) para mejorar el rendimiento del modelo seleccionado.
- Selección del mejor modelo basado en métricas de rendimiento como precisión, recall y F1-score.


Contacto
[Contáctame por correo electrónico](federicothione@gmail.com)
