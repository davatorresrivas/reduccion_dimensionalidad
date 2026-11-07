# Reducción de dimensionalidad mediante PCA

Aplicación de PCA al dataset Breast Cancer Wisconsin de Scikit-learn.

## Archivos
- `Reduccion_Dimensionalidad_PCA_Breast_Cancer.ipynb`: desarrollo reproducible.
- `Informe_Reduccion_Dimensionalidad_PCA.pdf`: informe académico.
- `figuras/`: visualizaciones.

## Ejecución
Abrir el notebook en Google Colab o Jupyter y ejecutar todas las celdas en orden. No requiere descargar datos externos.

## Resultados de referencia
- Observaciones: 569; variables: 30.
- Faltantes: 0; duplicados: 0.
- Varianza PC1+PC2: 63.24%.
- Componentes para 90%: 7; para 95%: 10.

PCA se ajusta solo con las variables predictoras. La etiqueta se reserva para visualización. Los atípicos detectados por IQR no se eliminan automáticamente.
