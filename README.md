
# 🧪 Clasificación de la Calidad del Agua del Río de la Plata

**Autor:** Diego Estrada  
**Proyecto Final - Aprendizaje Automático 2025**  
 

---

## 📑 Índice de Contenidos

1. **Descripción del Proyecto**
   - Contexto ambiental del Río de la Plata
   - Relevancia del análisis de calidad del agua
   - Objetivo general del proyecto

2. **Formulación del Problema**
   - Tipo de problema: Clasificación supervisada
   - Categorías de calidad del agua:  
     *Levemente deteriorada, Deteriorada, Muy deteriorada, Extremadamente deteriorada*
   - Variables predictoras: parámetros físico-químicos y microbiológicos

3. **Descripción del Dataset**
   - Origen de los datos: Ministerio de Ambiente, RIIGLO, Kaggle, CiAM
   - Periodo de recolección: 2013–2024
   - Estructura del dataset: 30 columnas, 1186 registros
   - Diccionario de variables

4. **Procesamiento ETL**
   - Unificación de datasets
   - Limpieza y estandarización de datos
   - Tratamiento de valores nulos y duplicados
   - Codificación de variables categóricas
   - Generación del dataset final: 1182 registros y 30 variables

5. **Análisis Exploratorio de Datos (EDA)**
   - Estadísticas descriptivas y visualización de distribuciones
   - Detección y tratamiento de outliers con IQR
   - Análisis de correlación entre variables
   - Distribución de la variable objetivo por año

6. **Modelado y Evaluación**
   - División de datos y balanceo con SMOTE
   - Reducción de dimensionalidad con PCA
   - Entrenamiento de modelos:
     - Random Forest
     - K-Vecinos más Cercanos (KNN)
     - Red Neuronal Multicapa (MLP)
   - Métricas de evaluación: Accuracy, F1-score, Matriz de Confusión
   - Curvas de aprendizaje

7. **Optimización de Modelos**
   - Búsqueda de hiperparámetros con GridSearchCV
   - Comparación de rendimiento entre modelos
   - Implementación de regularización y early stopping en MLP

8. **Conclusiones**
   - Comparativa de modelos
   - Selección del modelo óptimo
   - Recomendaciones para futuras mejoras
