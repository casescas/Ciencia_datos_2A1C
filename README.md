# 🧪 Clasificación de la Calidad del Agua del Río de la Plata

**Alumno:** Diego Estrada  
**Profesor:** Martin Mirabete

**Proyecto Final - Aprendizaje Automático 2025**  

## 1. Introducción y Objetivo del Proyecto
📄 _Archivo: **Entrega 1, Descripción y Formulación del Objetivo 2.pdf**_
- Contexto ambiental del Río de la Plata
- Importancia del monitoreo de la calidad del agua
- Objetivo general del proyecto
- Tipo de problema, clasificación supervisada
- Categorías de calidad del agua: levemente deteriorada, deteriorada, muy deteriorada, extremadamente deteriorada
- Modelos propuestos: ANN, XGBoost, SVM, Random Forest, k-NN, Redes Neuronales.

## 2. Descripción del Dataset y Origen
📄 _Archivo: **Entrega 2, Descripción del Dataset y OrigenTarea 2.pdf**_
- Fuentes de datos: Kaggle, CiAM
- Periodo de recolección: 2013–2024
- Estructura del dataset: 30 variables, 1186 registros
- Variables físico-químicas, microbiológicas y estacionales
- Diccionario de datos
- Organización del proyecto con estructura Cookiecutter

## 3. Procesamiento ETL (Extracción, Transformación y Carga)
📄 _Archivo: **Procesamiento ETL - Dataset unificados 1.pdf**_
- Carga de archivos CSV con rutas relativas
- Unificación de datasets en un solo DataFrame
- Limpieza de datos:
  - Eliminación de columnas irrelevantes y duplicados
  - Tratamiento de valores nulos (mediana y moda)
  - Estandarización de texto y símbolos
- Codificación de variables:
  - Binarización de variables categóricas (presente/ausente)
  - One-Hot Encoding para estaciones del año
  - Ordinal Encoding para la variable objetivo

## 4. Análisis Exploratorio de Datos (EDA)
📄 _Archivo: **Exploratorio y Entrenamiento Modelos.pdf**_
- Estadísticas descriptivas
- Visualización de distribuciones y detección de outliers
- Matriz de correlación y mapa de calor
- Análisis de desbalance de clases

## 5. Preprocesamiento para Modelado
- Balanceo de clases con SMOTE
- Estandarización de variables
- Reducción de dimensionalidad con PCA

## 6. Modelado y Evaluación de Algoritmos
- Modelos aplicados:
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Red Neuronal Multicapa (MLP)
- Evaluación con métricas: accuracy, precision, recall, F1-score
- Curvas de aprendizaje
- Observaciones sobre overfitting y rendimiento por clase

## 7. Optimización de Modelos
- GridSearchCV para hiperparámetros
- Mejores configuraciones para cada modelo
- Comparación de resultados

## 8. Conclusiones Finales
- MLP optimizado como mejor modelo
- Preparación del modelo para uso futuro

## 9. Presentación del Modelo y Análisis de Resultados  
📄 _Archivo: **Entrega 3, Presentación del Modelo y Análisis de Resultados.pdf**_
- Revisión de fuentes de datos  
- Análisis exploratorio adicional  
  - Distribución de clases  
  - Correlaciones clave  
  - Visualizaciones (scatter, violin plots)  
  - Tratamiento de outliers  
  - PCA (25 componentes, 95% varianza)  
- Respuestas a preguntas de investigación:  
  1. Variables más influyentes  
  2. Diferencias estacionales y geográficas  
  3. Capacidad predictiva de los modelos  
- Métricas detalladas del modelo MLP  
- Conclusión: MLP como mejor modelo  