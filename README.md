# **Prácticas de Regresión Logística**

# **Cancer de Mama _(Diagnóstico)_** 🩺
Este proyecto pretende aplicar un modelo de regresión logística binomial para clasificar si una persona tiene un cancer benigno o maligno.

<img align="center" src="https://cdn-icons-png.flaticon.com/128/8357/8357361.png" alt='Cancer de mama'>

## Objetivo 🛣️

El objetivo es clasificar el tipo de cancer de mama según ciertas variables obtenidas de una imagen digitalizada de un núcleo celular de una masa mamaria.

## Metodología 💡

1. **Preprocesamiento de datos**: Se escalarán los datos utilizando la función `RobustScaler` de la librería `sklearn`.
2. **División de datos**: Se dividirán los datos en conjuntos de entrenamiento y prueba en una proporción de 80:20.
3. **Modelado**: Se utilizará el algoritmo `RegressionLogistic` del módulo `sklearn.linear_model`
4. **Evaluación**: Se evaluará el modelo utilizando las métricas `accuracy_score`, `precision_score`, `recall_score` y `f1_score`. Además de visualizar la matriz de confusión.