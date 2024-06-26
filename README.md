# Tesis-Maestria
Repositorio para el almacenamiento de los códigos utilizados en el proyecto de grado "Modelo de predicción de ausentismo laboral por incapacidad médica en una institución financiera colombiana".

En el proyecto se exploran diversos modelos para la predicción de incapacidades laborales en una institución financiera colombiana. Dichos modelos se abordan desde un enfoque de clasificación, con la implementación de algoritmos como Regresión Logística, Decision Tree y Random Forest, para predecir la ocurrencia o no ocurrencia de incapacidades, y desde un enfoque de regresión, con la implementación de modelos como regresión de Poisson, regresión Binomial Negativa, modelos inflados en cero, entre otros, para predecir el número de días de incapacidad, a partir de variables predictoras asociadas a los empleados, al tiempo y algunas variables macroeconómicas.


A continuación, se encuentra una breve explicación de los archivos almacenados:

- PredicciónIncapacidad_Clasificación: Corresponde al código utilizado en el enfoque de CLASIFICACIÓN, donde se tiene una variable objetivo binaria, que corresponde a la ocurrencia o no ocurrencia de incapacidad laboral. Contiene las siguientes secciones: Conexión Google Drive y definición de paths, cargue y lectura de datasets, construcción de dataset final, análisis exploratorio de datos, preprocesamiento e implementación de los modelos Regresión Logística, Decision Tree, Random Forest, XGBoost y SVM (con la librería Scikit Learn).

- PredicciónIncapacidad_Regresión1: Corresponde a un primer código utilizado en el enfoque de REGRESIÓN, donde se tiene una variable objetivo numérica, que corresponde al número de días de incapacidad laboral. Contiene las siguientes secciones: Conexión Google Drive y definición de paths, cargue y lectura de datasets, construcción de dataset final, análisis exploratorio de datos, preprocesamiento e implementación de los modelos Regresión de Poisson, Decision Tree, Random Forest y XGBoost, haciendo uso de la librería Scikit Learn.

- PredicciónIncapacidad_Regresión2: Corresponde a un segundo código utilizado en el enfoque de REGRESIÓN, donde se tiene una variable objetivo numérica, que corresponde al número de días de incapacidad laboral. Contiene las siguientes secciones: Conexión Google Drive y definición de paths, cargue y lectura de datasets, construcción de dataset final, análisis exploratorio de datos, preprocesamiento e implementación de los modelos Regresión de Poisson, Regresión Binomial Negativa, Regresión de Poisson con Inflación de Ceros y Regresión Binomial Negativa con Inflación de Ceros, usando la librería Statsmodels.

- DatasetFinal_Clasificación: Es el dataset obtenido luego de realizar el proceso de unificación de los datasets iniciales, la limpieza de los datos, y la construcción y selección de variables requeridas en el caso del enfoque de clasificación. Sobre este dataset se implementan los modelos Regresión Logística, Decision Tree, Random Forest, XGBoost y SVM.
  
- DatasetFinal_Regresión: Es el dataset obtenido luego de realizar el proceso de unificación de los datasets iniciales, la limpieza de los datos, y la construcción y selección de variables requeridas en el caso del enfoque de regresión, y la única diferencia con el DatasetFinal_Clasificación es la variable objetivo (que deja de ser binaria para convertirse en numérica). Sobre este dataset se implementan los modelos Regresión de Poisson, Regresión Binomial Negativa, Regresión de Poisson con Inflación de Ceros, Regresión Binomial Negativa con Inflación de Ceros, Decision Tree, Random Forest y XGBoost.
  

Estudiante: Laura Margarita Guerrero Guerra
