## Trabajos realizados para la materia de Organización de Datos en la Universidad de Buenos Aires. 

En el **Trabajo Práctico I** se nos otorgó un dataset que contaba con reservas de hotel, y su objetivo era el de predecir si una reserva iba a ser cancelada. Para la ejecución de esto, realizamos un preprocesamiento que constó de:
* una búsqueda de valores atípicos, tanto univariados como multivariados
* datos faltantes
* máximos, mínimos, media, mediana
* análisis de correlaciones entre las variables

para lo cual nos fueron útiles los gráficos como heatmaps con coeficiente de Pearson, histogramas, boxplots, barplots, de dispersión, etc. 
Una vez hecho esto, construímos distintos modelos de clasificación entre los que destacamos:
* Árboles de decisión
* K Nearest Neighbors
* Support Vector Machines
* XGBoost
* Ensambles híbridos tipo voting y stacking
* Redes Neuronales
Optimizamos sus hiperparámetros usando K-folds Cross Validation y evaluamos sus performances analizando las matrices de confusión y métricas como accuracy y F1-Score.
Finalmente conseguimos predecir correctamente el estado de la reserva con un éxito del 82%.  

En el **Trabajo Práctico II** se nos otorgó un dataset que contaba con críticas cinematográficas en español, y su objetivo era el de calificar esta crítica, mediante el análisis del habla, como positiva o negativa. Para ello se realizó un preprocesamiento del texto, en el cual eliminamos las tildes, pasamos las mayúsculas a minúsculas, eliminamos los caracteres que no fuesen alfabéticos, los conectores, palabras de una sola letra o de dos. Luego, se utilizó el modelo de bag of words para la conversión de las palabras a vectores, y construimos modelos de predicción entre los que destacamos:
* Bayes Naive, multinomial y Bernoulli
* Random Forest
* XGBoost
* Redes neuronales, usando Keras y Tensorflow
* Ensambles de tipo voting

Optimizamos sus hiperparámetros usando K-folds Cross Validation y evaluamos sus performances analizando las matrices de confusión y métricas como accuracy y F1-Score. Finalmente conseguimos predecir correctamente la intención de la reseña con un éxito del 78%. 
