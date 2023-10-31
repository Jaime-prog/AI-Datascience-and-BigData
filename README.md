# AI-Datascience-and-BigData
Este repositorio aplica herramientas de IA y big data para realizar análisis de ciencia de datos en un gran conjunto de datos de reseñas de Amazon. Se centra en el procesamiento de datos, la visualización y el aprendizaje automático utilizando PySpark.

## Procesamiento y visualización de datos

El conjunto de datos principal utilizado es un archivo CSV de reseñas de Amazon de más de 1 GB de tamaño, al que se accede desde Kaggle: [Amazon Reviews Dataset](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data).

Utilizando PySpark y las librerías asociadas, esta sección realiza el ETL y el preprocesamiento de los datos sin procesar de las reseñas de Amazon. El objetivo es extraer los atributos clave, transformarlos en un formato estructurado y cargarlos en un marco de datos PySpark para su análisis.

Las visualizaciones se crean utilizando el software Tableau para proporcionar información sobre los datos procesados, incluyendo:

- Reseñas a lo largo del tiempo
- Reseñas por categoría de producto
- Recuento de palabras en las reseñas
- Valoraciones medias por producto
- Principales palabras clave en las reseñas

Tableau se conecta directamente al marco de datos de PySpark para crear cuadros de mando interactivos para explorar el conjunto de datos de reseñas de Amazon.

## Creación de modelos de aprendizaje automático

A partir de los datos estructurados de la canalización PySpark, esta sección entrena modelos de aprendizaje automático para realizar tareas como la predicción de valoraciones, la clasificación de textos, etc. Se utilizan modelos como la regresión lineal, los bosques aleatorios y SVM.

El proceso incluye pasos como la ingeniería de características, el entrenamiento/validación de modelos y el seguimiento del rendimiento de los modelos. Para evaluar los resultados se utilizan visualizaciones y métodos de interpretación de modelos.

## Documentación

El repositorio incluye un informe completo en el que se documentan los objetivos del proyecto, los conjuntos de datos, los pasos del procesamiento de datos, los modelos utilizados, los resultados y las principales conclusiones. El informe proporciona una narración completa del proceso de aprendizaje automático de principio a fin aplicado a los datos de las revisiones de Amazon.
