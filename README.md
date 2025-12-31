# Practica-algegra-101
# Práctica Final: Regresión Lineal con Descenso del Gradiente

Este proyecto implementa y valida el algoritmo de **descenso del gradiente** para ajustar un modelo de regresión lineal sobre el conjunto de datos Auto MPG. El objetivo es predecir el consumo de combustible (mpg) en función del peso del vehículo.

---

## 📑 Contenido

- Preprocesamiento de datos: selección de variables y escalado
- Implementación manual del descenso del gradiente
- Comparación con mínimos cuadrados (OLS)
- Visualización de la recta ajustada y evolución del error
- Ajuste de hiperparámetros (`eta`, número de iteraciones)
- Interpretación de resultados

---

## 🗃️ Dataset

- Fuente: UCI Machine Learning Repository  
- Variables usadas:
  - `weight`: peso del vehículo (predictor)
  - `mpg`: millas por galón (variable objetivo)

---

## 🧠 Algoritmo

Se implementa el descenso del gradiente desde cero:

```python
w = w - eta * grad
