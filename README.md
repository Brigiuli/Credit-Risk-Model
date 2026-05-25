Predicción de Impago de Préstamos

## Resumen del Proyecto

Este proyecto tiene como objetivo analizar datos de préstamos financieros y desarrollar un modelo de Machine Learning capaz de predecir el riesgo de impago de los clientes. A través del análisis exploratorio de datos (EDA) y modelos de clasificación, se identificaron patrones asociados al incumplimiento de pagos, permitiendo apoyar la toma de decisiones crediticias en instituciones financieras.

## Objetivos
## Objetivo General
Desarrollar un modelo predictivo que permita identificar clientes con alto riesgo de impago de préstamos para mejorar la evaluación crediticia y reducir pérdidas financieras.

## Objetivos Específicos
Limpiar y preparar el dataset para el análisis y modelado.
Identificar variables relevantes relacionadas con el impago.
Construir y evaluar modelos de clasificación.
Analizar métricas de desempeño del modelo.
Generar insights para apoyar decisiones del negocio.

## Metodología
El proyecto incluye varios enfoques de ciencia de datos:
* Descarga y carga del dataset desde Kaggle.
* Limpieza y preparación de datos.
* Análisis exploratorio de datos (EDA).
* Transformación y codificación de variables categóricas.
* División de datos en entrenamiento y prueba.
* Entrenamiento de modelos de clasificación.
* Evaluación mediante métricas como accuracy, precision, recall y matriz de confusión.
* Interpretación de resultados y hallazgos de negocio.

## Principales insights
* Clientes con menor ingreso presentan mayor riesgo de impago.
* Un bajo credit score está asociado a mayor morosidad.
* Altas tasas de interés y elevados montos de préstamo incrementan el riesgo.
* Clientes con historial financiero más estable muestran menor probabilidad de incumplimiento.
* Variables como ingresos, DTI ratio y credit score fueron determinantes para la predicción.

## Herramientas Utilizadas
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Google Colab | Kaggle

## Conjunto de Datos
Fuente: Kaggle
Dataset: Loans and Liability Dataset
Registros: 255,347 filas
Variables: 18 columnas
Tipo de problema: Clasificación binaria
Variable objetivo: Default (1 = incumplimiento, 0 = no incumplimiento)

El dataset contiene información demográfica, financiera y crediticia de clientes, incluyendo ingresos, monto del préstamo, tasa de interés, historial crediticio y variables relacionadas con el comportamiento de pago.
https://www.kaggle.com/datasets/nikhil1e9/loan-default
