# Clasificación SVM en Datos Laborales: Comparación de Kernels y Predicción

Este repositorio presenta un proyecto de clasificación basado en Máquinas de Vectores de Soporte (SVM), aplicado al análisis de datos de empleados. Se implementan distintos kernels para evaluar el rendimiento del modelo y se aplica una predicción sobre nuevos casos reales.

## Contenido del proyecto

- Carga y preparación de los datos:
  - Codificación de variables categóricas con `get_dummies`
  - Separación entre variables explicativas (X) y objetivo (y)
  - Normalización para mejorar el rendimiento del modelo

- Modelado con SVM:
  - Aplicación de kernels: lineal, polinomial, RBF y sigmoide
  - Evaluación con matriz de confusión y reportes de clasificación
  - Visualización con mapas de calor para cada kernel

- Comparación de modelos:
  - Análisis de desempeño para determinar el kernel óptimo
  - Justificación basada en precisión, recall, F1-score

- Predicción aplicada:
  - Evaluación de un nuevo empleado utilizando el modelo entrenado con kernel RBF

## Conclusiones

- El modelo SVM con kernel RBF mostró el mejor rendimiento general.
- Las visualizaciones ayudaron a interpretar los resultados de forma clara.
- El proceso de predicción se adaptó correctamente al flujo de trabajo completo.

## Requisitos técnicos

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Seaborn  
- Matplotlib

## Recomendación

Este proyecto es ideal para aprender cómo comparar modelos SVM y aplicar técnicas de clasificación en escenarios reales. Perfecto para quienes buscan mejorar su dominio de machine learning supervisado en Python.
