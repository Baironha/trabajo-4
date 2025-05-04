# Modelo de Predicción de Cáncer de Mama

## Variables de Entrada:
- `breast_cancer_wisconsin.csv`: Archivo CSV con los datos del cáncer de mama. Debe contener las columnas correspondientes a los atributos de los pacientes.

## Variables de Salida:
- El modelo devuelve una predicción binaria:
  - `0`: No cáncer (benigno).
  - `1`: Cáncer (maligno).

## Funciones del Modelo:
- **Entrenamiento**: Entrena un modelo de regresión logística utilizando `GridSearchCV` para encontrar los mejores hiperparámetros.
- **Evaluación**: El modelo es evaluado con el conjunto de datos de prueba y se calculan las métricas de precisión, matriz de confusión, y la curva ROC.
