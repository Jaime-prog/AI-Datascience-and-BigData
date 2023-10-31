# AI-Datascience-and-BigData
Este repositorio aplica herramientas de IA y big data para realizar análisis de ciencia de datos en un gran conjunto de datos de reseñas de Amazon. Se centra en el procesamiento de datos, la visualización y el aprendizaje automático utilizando PySpark.

## Procesamiento y visualización de datos

El conjunto de datos principal utilizado es un archivo CSV de reseñas de Amazon de más de 1 GB de tamaño, al que se accede desde Kaggle: [Amazon Reviews Dataset](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data).

Utilizando PySpark y las librerías asociadas, esta sección realiza el ETL y el preprocesamiento de los datos sin procesar de las reseñas de Amazon. El objetivo es extraer los atributos clave, transformarlos en un formato estructurado y cargarlos en un marco de datos PySpark para su análisis. Este se encuentra en el siguiente notebook:

[Processing and visualisation of big data Jaime.ipynb](Processing_and_visualisation_of_big_data_Jaime.ipynb)

Las visualizaciones se crean utilizando el software Tableau para proporcionar información sobre los datos procesados. Los cuales están dentro del: `Informe de Procesamiento y Análisis de Big Data`

## Creación de modelos de aprendizaje automático

Dada la naturaleza del problema abordado, consistente en la clasificación de reseñas en positivas o negativas, se determinó que se trataba de una tarea de clasificación binaria. Se optó por implementar un modelo de regresión logística para la predicción de la variable objetivo. Esta técnica supervisada permite predecir la probabilidad de que una instancia pertenezca a una categoría en particular, mediante la estimación de funciones logísticas aplicadas a las variables independientes.



