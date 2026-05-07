# Proyecto Programado I — Machine Learning

**Curso:** IC-6200 / Inteligencia Artificial  
**Institución:** Tecnológico de Costa Rica  

Este repositorio contiene un extenso portafolio práctico implementado en un cuaderno de Jupyter (`ProyectoIA.ipynb`), en el cual se desarrollan, evalúan y comparan tres familias principales de algoritmos de Machine Learning (supervisados y no supervisados) aplicados a diversos conjuntos de datos reales.

## 📊 Algoritmos y Datasets Analizados

### 1. Regresión Logística (Clasificación Binaria)
Se utiliza la regresión logística para predecir probabilidades y clasificar en dos categorías.
*   **Students Performance (Desempeño Estudiantil):** Predicción de si un estudiante aprueba o reprueba matemáticas en función de sus condiciones sociodemográficas y puntajes de lectura/escritura.
*   **Wine Quality (Calidad del Vino Blanco):** Predicción de si un vino es de alta calidad basándose en sus características fisicoquímicas, manejando un dataset con desbalance de clases.

### 2. K-Nearest Neighbors - KNN (Clasificación y Regresión)
Demostración de la versatilidad del algoritmo KNN para problemas tanto discretos como continuos.
*   **Netflix (Clasificación):** Identificación del tipo de contenido (Película o Programa de TV) apoyándose principalmente en los géneros y la duración.
*   **Life Expectancy OMS (Regresión):** Predicción de la expectativa de vida en años según indicadores de salud, sociales y de desarrollo económico por país.

### 3. Clustering (Aprendizaje No Supervisado)
Agrupación de datos sin etiquetas usando **K-Means** y **GMM (Gaussian Mixture Models)** / **DBSCAN**.
*   **Credit Card Fraud Detection:** Segmentación de transacciones de tarjetas de crédito para identificar y detectar anomalías (fraude) de forma natural sin usar la etiqueta objetivo durante el entrenamiento.
*   **Telco Customer Churn:** Segmentación de clientes de telecomunicaciones según su perfil y comportamiento de uso para identificar grupos con distinto riesgo de abandono del servicio (churn).

## 🛠️ Metodología Aplicada

Para cada uno de los modelos implementados en el cuaderno, se sigue de manera rigurosa el siguiente flujo de trabajo de Ciencia de Datos:
1. **Carga y Exploración Inicial:** Comprensión de las variables y estructura de los datos.
2. **Análisis Exploratorio de Datos (EDA):** Visualización de distribuciones, correlaciones y relaciones entre variables.
3. **Preprocesamiento:** Escalado de datos (fundamental para algoritmos basados en distancias como KNN y K-Means), codificación de variables categóricas, y técnicas de manejo de desbalanceo y outliers.
4. **Entrenamiento y Ajuste de Hiperparámetros:** Técnicas de optimización como la búsqueda del K óptimo mediante validación cruzada y el método del codo/silueta para Clustering.
5. **Evaluación de Modelos:** Análisis de resultados usando múltiples métricas como Accuracy, Precision, Recall, F1-Score, AUC-ROC, RMSE, MAE y R² Score.

## 🚀 Cómo utilizar este proyecto

Para reproducir el análisis, abre el cuaderno principal:
```bash
jupyter notebook ProyectoIA.ipynb
```

*Nota: Asegúrate de tener instaladas las dependencias típicas de ciencia de datos en Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).*