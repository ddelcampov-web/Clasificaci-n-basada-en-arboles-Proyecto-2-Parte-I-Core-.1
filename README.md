# Clasificaci-n-basada-en-arboles-Proyecto-2-Parte-I-Core-.1
# Proyecto 2: Análisis Inicial y Selección de Problema

## Descripción
Este proyecto tiene como objetivo realizar un análisis exploratorio inicial de tres conjuntos de datos. Se busca comparar distintas opciones y seleccionar una problemática para continuar con un modelo de Machine Learning.

## Conjuntos de Datos Analizados

### 1. Iris
- Fuente: Scikit-learn / UCI Machine Learning Repository.
- Tamaño: 150 filas.
- Problema sugerido: clasificación multiclase.
- Objetivo: predecir la especie de flor según medidas de sépalos y pétalos.

### 2. Breast Cancer Wisconsin
- Fuente: Scikit-learn / UCI Machine Learning Repository.
- Tamaño: 569 filas.
- Problema sugerido: clasificación binaria.
- Objetivo: predecir si un tumor es benigno o maligno.
- https://colab.research.google.com/drive/1wYrQu61aYp_qDgmw6l_cHCzgS-jw6oim?usp=sharing

### 3. Diabetes
- Fuente: Scikit-learn.
- Tamaño: 442 filas.
- Problema sugerido: regresión.
- Objetivo: predecir la progresión de la diabetes a partir de variables clínicas.
- https://colab.research.google.com/drive/19Ozyi6H3ckg6WdXLijtdYTZKkMwN88Sd?usp=sharing

## Resumen del EDA Inicial
Se realizó una exploración inicial de los tres datasets incluyendo:
- Revisión de estructura.
- Estadísticas descriptivas.
- Identificación de valores nulos.
- Identificación de duplicados.
- Visualización de distribuciones.
- Boxplots para detección de outliers.
- Mapa de calor de correlaciones.

Los tres datasets permiten desarrollar un análisis claro sin una carga excesiva de limpieza.

## Problema Seleccionado
Se seleccionó el dataset **Breast Cancer Wisconsin**.

### Justificación
Este dataset fue elegido porque:
- Permite trabajar un problema de clasificación binaria.
- Tiene una aplicación relevante en salud.
- Sus variables numéricas permiten realizar análisis estadístico, correlaciones, visualizaciones y modelado predictivo.

### Problemática
Predecir si un tumor es benigno o maligno a partir de características numéricas extraídas de imágenes médicas.

### Objetivo Específico
Construir un modelo de clasificación binaria que permita predecir la clase del tumor usando variables clínicas del dataset.

## Estructura del Repositorio

```text
/Proyecto2
|-- /datasets
|   |-- iris.csv
|   |-- breast_cancer.csv
|   |-- diabetes.csv
|-- /EDA
|   |-- EDA_iris.ipynb
|   |-- EDA_breast_cancer.ipynb
|   |-- EDA_diabetes.ipynb
|-- /selected_dataset
|   |-- selected_dataset.csv
|   |-- EDA_selected_dataset.ipynb
|-- README.md
```

## Autores
- Daniela del Campo: análisis exploratorio, selección de problema y documentación.

## Licencia
Uso académico y educativo.
