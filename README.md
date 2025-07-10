# 🫀 Heart Failure Prediction Analysis

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo predecir la **probabilidad de fallo cardíaco** utilizando un conjunto de datos público disponible en **Kaggle**. El análisis incluye la carga de datos, exploración, preprocesamiento y la implementación de modelos de aprendizaje automático para predecir la presencia de enfermedades cardíacas.

---

## 📊 Dataset

El conjunto de datos utilizado es **"Heart Failure Prediction"** de Kaggle, que contiene **918 registros** y **12 características** relacionadas con la salud cardiovascular:

- `Age` — Edad  
- `Sex` — Sexo  
- `ChestPainType` — Tipo de dolor en el pecho  
- `RestingBP` — Presión arterial en reposo  
- `Cholesterol` — Colesterol  
- `FastingBS` — Azúcar en sangre en ayunas  
- `RestingECG` — Electrocardiograma en reposo  
- `MaxHR` — Frecuencia cardíaca máxima  
- `ExerciseAngina` — Angina inducida por ejercicio  
- `Oldpeak` — Depresión del segmento ST  
- `ST_Slope` — Pendiente del segmento ST  
- `HeartDisease` — **Variable objetivo** (0 = No, 1 = Sí)  

---

## 🗂️ Estructura del Proyecto

El proyecto está organizado en el archivo `Prediccion_Cora.ipynb`, que incluye las siguientes secciones:

1. **Carga de Paquetes**  
   Importación de bibliotecas como `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `catboost` y `xgboost`.

2. **Carga de Datos**  
   Descarga desde Kaggle y carga en un `DataFrame`.

3. **Análisis Exploratorio (EDA)**  
   - Información general del dataset  
   - Estadísticas descriptivas  
   - Detección de valores faltantes  
   - Visualización de distribuciones y correlaciones

4. **Preprocesamiento**  
   - División en conjunto de entrenamiento y prueba  
   - Escalado de características

5. **Modelado**  
   - Implementación de modelos como `RandomForestClassifier`, `CatBoostClassifier` y `XGBClassifier`  
   - Optimización de hiperparámetros con `GridSearchCV`  
   - Evaluación con métricas como **Accuracy**, **AUC-ROC**, y **F1-score**

6. **Resultados**  
   - Comparación de rendimiento  
   - Selección del mejor modelo

---

## 🛠️ Requisitos

Instala las bibliotecas necesarias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost xgboost kagglehub
```

## 👤 Autor
Pedro David Yacila Aramburú
Estudiante de Ingeniería Estadística e Informática
Apasionado por el análisis de datos, machine learning 

## 📫 Contacto
GitHub: YacilaPedro

LinkedIn: https://www.linkedin.com/in/pedro-david-yacila-5a2868264/
