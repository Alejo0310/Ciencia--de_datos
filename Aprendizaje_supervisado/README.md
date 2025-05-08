**Aprendizaje supervisado** 

**Alejandro Pérez Ospina**

Base de datos: Credit Risk Benchmark Dataset
Fuente: Kaggle - Credit Risk Benchmark Dataset

El presente trabajo aplica técnicas de aprendizaje supervisado con el objetivo de predecir la probabilidad de que un individuo incurra en una mora superior a 90 días durante los próximos dos años, utilizando como variable objetivo dlq_2yrs. La base de datos utilizada contiene información financiera detallada de clientes, incluyendo variables como ingresos anuales, número de cuentas abiertas, moras previas, proporción de deuda sobre ingresos, entre otras.

Se construyen y comparan tres modelos de clasificación: regresión logística, árbol de decisión y K-Nearest Neighbors (KNN). Estos modelos permiten identificar patrones que diferencian a los clientes que tienen alto riesgo de mora de aquellos con bajo riesgo. El conjunto de datos fue dividido en entrenamiento (80%) y prueba (20%) para evaluar el desempeño de los modelos de forma objetiva.

Las métricas utilizadas para la evaluación incluyen precisión (accuracy), matriz de confusión, curva ROC-AUC y importancia de variables (permuta), lo cual permite interpretar tanto el rendimiento como la relevancia de las características en la toma de decisiones del modelo.