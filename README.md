
En el siguiente repositorio buscaremos aplicar Redes Neuronales al análisis y detección de diabetes. 

El dataset utilizado es el Diabetes Health Indicators Dataset proveniente de la encuesta Behavioral Risk Factor Surveillance System (BRFSS). La misma es una encuesta telefonica recolectada anualmente por la CDC donde a partir de una combinación de datos se busca detectar la presencia o no de diabetes o prediabetes.   

El repositorio trae tres datasets, en este caso utilizaremos el 2 y el 3 que poseen la misma información solo que el 2 posee 70692 datos con balanceo y el 3 posee 253680 datos pero desbalanceados. El 1 decidimos no utilizarlo ya que tiene 3 clases en la variable target Diabetes_012  (diabetes, prediabetes o no_diabetes) mientras que los otros dos poseen ambos 2 clases en la variable target Diabetes_binary  (diabetes/prediabetes y no_ diabetes). 

Decidimos utilizar los dos a fin de evaluar el comportamiento de la red con un dataset balanceado vs uno desbalancedo

Para realizar el análisis exploratorio de datos (EDA) utilizamos SweetViz...


Repositorio de práctica de Introducción al Deep Learning. 

Dataset Kaggle. 

https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/