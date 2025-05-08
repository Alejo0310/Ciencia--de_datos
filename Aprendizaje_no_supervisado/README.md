# Clustering de Empresas Tecnológicas con PCA y K-Means

Este proyecto aplica técnicas de aprendizaje no supervisado sobre datos bursátiles históricos de cinco grandes empresas tecnológicas: **Apple (AAPL), Amazon (AMZN), Google (GOOGL), Microsoft (MSFT) y NVIDIA (NVDA)**. Los datos abarcan desde enero de 2010 hasta enero de 2025, con información diaria sobre precios de apertura, cierre, máximos, mínimos y volumen de negociación.

## Objetivos

- Aplicar análisis de componentes principales (PCA) para reducir la dimensionalidad del conjunto de datos.
- Visualizar los datos reducidos a dos componentes principales y observar posibles formaciones de grupos.
- Aplicar técnicas de selección de características para eliminar redundancias.
- Ejecutar el algoritmo de clustering **K-means** en tres versiones del conjunto de datos:
  - Datos originales
  - Datos reducidos mediante PCA
  - Datos reducidos mediante selección de características
- Evaluar la calidad del agrupamiento usando el **método del codo** y el **silhouette score**.
- Comparar los resultados obtenidos con cada enfoque.

## Principales hallazgos

- El método del codo indicó un número óptimo de clusters similar en los tres enfoques.
- El enfoque con PCA permitió visualizar claramente la formación de grupos al reducir a dos dimensiones.
- El dataset reducido por correlación conservó características relevantes y eliminó redundancias sin perder estructura útil.
- El **silhouette score** más alto se obtuvo con el conjunto reducido por correlación, indicando mejor separación entre clusters.
- El enfoque con PCA, aunque útil para visualización, perdió algo de información relevante en comparación con el original y el reducido por selección.
