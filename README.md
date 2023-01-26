# Datathon-Henry-Labs-Proyecto Individual 2 

¡Bienvenidos a mi segundo proyecto!😀

En esta oportunidad, el trabajo desarrollado consiste en la elaboración de un modelo de Maching Learning. Para mas detalles de la consigna, siga el siguiente enlace👉
https://github.com/soyHenry/Datathon.

# Resumen

La actividad consiste en elaborar un modelo que prediga  si una propiedad inmobiliaria pertenece a la  categoría de pecios bajos (low) o no: en éste caso se utilizarán como métricas de evaluación para aprendizaje supervisado "Accuracy" y "Recall". Y para el caso de modelos de aprendizaje no-supervisado (en cual se deberán clasificar las propiedades en las categorias de low-medium-high (bajo-medio-alto)) se utilizará cómo métrica evaluatoria Silhouette score.

# Contenido
  A continuación se detalla el contenido de éste repositorio, con el enlace que los remite:
  
  
  - En el primer archivo "Eda" se encuentra el desarrollo del código comentado de la exploración y análisis de los datos provistos, en detalle : [Enlace]                   https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/EDA.ipynb
  - En el segundo archivo "Modelo_DTC, se continúa con el análisis del paso anterior y se desarrolla el primer modelo "DecisionTreeClassifier", el código y 
    desarrollo se encuentra comentado: [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_DTC.ipynb
  - En el tercer archivo "Pruebas_con_train", podrán visualizar el análisis en detalle del mismo modelo implementado en el paso anterior (DTC) pero en el  set de             entrenamiento, con sus respectivas metricas, que sirvieron de base para el desarrollo de modelos posteriores: [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Pruebas_con_train.ipynb
  - En archivo "Modelo_Regresion_Logistica", observarán el código comentado del modelo de maching learning de regresion logística desarrollado: [Enlace] 
    https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_Regresion_Logistica.ipynb
  - El archivo "Modelo_Knn" contiene el desarrollo del modelo KNeighborsClassifier, donde se implementa una optimización de hiperparámetros con una grilla para random       search (codigo comentado):[Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_Knn.ipynb
  - El archivo "No-Supervisado" contiene el modelo Kmeans, su código comentado y desarrollo: [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/No-supervisado.ipynb


# Archivos CSV

En el repositorio se encuentran tambien los archivos csv con las predicciones de cada modelo, con su nombre para mejor identificacion. Ademas podrán encontrar el archivo "train_con_eda", que contiene el archivo train luego del EDA.

 - "DecisionTreeClassifier" . [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_DTC.csv
 - "Regresion_Logistica" . [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_Regresion_Logistica.csv
 - "KNeigborsClassifier" [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_Knn.csv
 - "Kmeans"- No supervisado [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/Modelo_No_supervisado.csv
 -  Tambien para cualquier consulta, se encuentra el csv con el set de entrenamiento ya con Eda implementado [Enlace] https://github.com/SoleGon/Datathon-Henry-Labs2/blob/main/train_con_eda

# Nota

Cada modelo supervisado de maching learning desarrollado, sirvio de base para ir optimizándolos a medida que trabajaba en el siguiente; espero que puedan disfrutarlos!


Y a predecir precios de propiedades!







![propiedades](https://user-images.githubusercontent.com/108495374/214704821-f4b02519-c025-493b-8bb9-ff9be1a31271.jpg)



