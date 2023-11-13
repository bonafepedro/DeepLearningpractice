
# Redes Neuronales para la Detección de Diabetes
## Introducción
En este repositorio, exploraremos la aplicación de Redes Neuronales para el análisis y detección de diabetes utilizando el Diabetes Health Indicators Dataset. Las redes neuronales simples se utilizarán como clasificadores para determinar la presencia o ausencia de diabetes o prediabetes en función de los datos recopilados a través de la encuesta Behavioral Risk Factor Surveillance System (BRFSS), una encuesta telefónica anual realizada por los Centros para el Control y la Prevención de Enfermedades (CDC).

## Dataset
El dataset utilizado proviene de Kaggle y se compone del Diabetes Health Indicators Dataset obtenido de la BRFSS. Este conjunto de datos contiene información recopilada a través de la encuesta telefónica, donde se busca identificar la presencia de diabetes o prediabetes mediante una combinación de factores de salud.

El repositorio incluye tres conjuntos de datos. En este trabajo, nos enfocaremos en los conjuntos de datos 2 y 3. El conjunto de datos 2 consta de 70,692 datos con un equilibrio entre las clases, mientras que el conjunto de datos 3 contiene 253,680 datos pero presenta desbalanceo en las clases. Optamos por no utilizar el conjunto de datos 1 debido a la presencia de tres clases en la variable objetivo (diabetes, prediabetes o no diabetes), a diferencia de los otros dos conjuntos que tienen dos clases (diabetes/prediabetes y no diabetes).

La elección de utilizar ambos conjuntos de datos nos permite evaluar el rendimiento de la red neuronal en un escenario balanceado y desbalanceado.

## Trabajo Realizado
Para realizar el análisis exploratorio de datos (EDA), empleamos SweetViz, una herramienta que proporciona visualizaciones detalladas y estadísticas descriptivas para comprender mejor la distribución y las relaciones en el conjunto de datos.

Como redes probamos la utilización de las dos librerías más comunes TensorFlow y Pytorch. En el modelo construido con TensorFlow utilizamos una arquitectura de dos capas ocultas con 4 y 2 neuronas y una función de activación ReLu. Como función de loss se utilizamos binary_crossentropy.
Con Pytorch probamos la construcción de dos modelos. El primero con dos capas ocultas de 4 y 8 neuronas con función de activación ReLu, una capa de clasificación con una sola neurona y función Sigmoid. Como función de pérdida Entropy Loss Binaria Cruzada. El segundo modelo fue de dos capas ocultas con 8 y 4 neuronas, con función de activación ReLu, una capa de clasificación con dos neuronas. La función de pérdida Cross Entropy Loss. 

## Estructura del Repositorio
El repositorio está organizado como un proyecto de práctica de Introducción al Deep Learning. Puedes encontrar los conjuntos de datos, el código fuente y otros recursos relacionados en las carpetas correspondientes.

## Enlaces

[Dataset Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/)
