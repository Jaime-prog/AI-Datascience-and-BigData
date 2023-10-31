# AI-Datascience-and-BigData
Este repositorio aplica herramientas de IA y big data para realizar análisis de ciencia de datos en un gran conjunto de datos de reseñas de Amazon. Se centra en el procesamiento de datos, la visualización y el aprendizaje automático utilizando PySpark.

## Procesamiento y visualización de datos

El conjunto de datos principal utilizado es un archivo CSV de reseñas de Amazon de más de 1 GB de tamaño, al que se accede desde Kaggle: [Amazon Reviews Dataset](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data).

Utilizando PySpark y las librerías asociadas, esta sección realiza el ETL y el preprocesamiento de los datos sin procesar de las reseñas de Amazon. El objetivo es extraer los atributos clave, transformarlos en un formato estructurado y cargarlos en un marco de datos PySpark para su análisis. Este se encuentra en el siguiente notebook:

[Processing and visualisation of big data Jaime.ipynb](Processing_and_visualisation_of_big_data_Jaime.ipynb)

Las visualizaciones se crean utilizando el software Tableau para proporcionar información sobre los datos procesados. Los cuales están dentro del: `Informe de Procesamiento y Análisis de Big Data`

## Creación de modelos de aprendizaje automático

A partir de los datos estructurados de la canalización PySpark, esta sección entrena modelos de aprendizaje automático para realizar tareas como la predicción de valoraciones, la clasificación de textos, etc. Se utilizan modelos como la regresión lineal, los bosques aleatorios y SVM.



