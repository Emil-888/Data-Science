# 📊 Proyecto de Data Science: Aprendizaje No Supervisado con K-Means

Este proyecto fue desarrollado en el entorno de **Google Colab** y se enfoca en la implementación del algoritmo de clustering **K-Means** para encontrar patrones y agrupaciones ocultas en los datos.

## 📈 Descripción del Proyecto
El objetivo principal de este análisis es segmentar un conjunto de datos para descubrir estructuras e insights que ayuden a la toma de decisiones. 

## 📂 Estructura de los Datos
El modelo procesa un conjunto de datos en formato `.csv` que cuenta con las siguientes características:
* **Volumen:** ~20,000 filas.
* **Dimensiones:** 14 columnas (variables analizadas).
* **Tipo de datos:** Variables numéricas y categóricas preprocesadas.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Python** (Entorno de desarrollo: Google Colab / Jupyter)
* **Pandas & NumPy:** Para la manipulación y limpieza de los datos.
* **Scikit-Learn:** Específicamente el módulo `cluster.KMeans` para el entrenamiento del algoritmo.
* **Matplotlib & Seaborn:** Para la visualización de los clústeres y el método del codo (Elbow Method).

## 🚀 Pasos Clave del Algoritmo
1. **Análisis Exploratorio (EDA):** Inspección inicial de las 20,000 filas.
2. **Preprocesamiento:** Escalamiento de variables (esencial para K-Means).
3. **Método del Codo:** Determinación del número óptimo de clústeres (K).
4. **Entrenamiento:** Ajuste del modelo K-Means y asignación de etiquetas a los datos.
5. **Visualización:** Gráficos interactivos y estáticos de los grupos resultantes.

---
*Nota: Este proyecto forma parte de mi formación académica en Data Science y Machine Learning.*
