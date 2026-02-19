# KAGGLE-COMPETICI-N# 💻 Laptop Price Prediction | Kaggle Machine Learning Project

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo predecir el **precio de portátiles** utilizando técnicas de Machine Learning a partir de sus características técnicas.

Se ha desarrollado un pipeline completo que incluye:

* Limpieza de datos
* Feature engineering
* Codificación de variables categóricas
* Entrenamiento del modelo
* Generación del archivo de submission para Kaggle

La métrica de evaluación utilizada es **RMSE (Root Mean Squared Error)**.

---

## 🎯 Objetivo

Construir un modelo capaz de estimar el precio de un portátil minimizando el error de predicción.

---

## 📊 Dataset

El dataset contiene información sobre:

* Marca
* Tipo de portátil
* RAM
* Peso
* CPU
* GPU
* Resolución de pantalla
* Tipo y tamaño de memoria
* Sistema operativo

Variable objetivo:

```
Price_in_euros
```

---

## ⚙️ Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 🧠 Feature Engineering

Se han creado nuevas variables para mejorar el rendimiento del modelo:

* 🔹 Velocidad del procesador en GHz
* 🔹 Marca del CPU
* 🔹 Presencia de SSD
* 🔹 Tamaño de la memoria
* 🔹 Pantalla Full HD

Estas transformaciones permiten que el modelo capture mejor la relación entre las características y el precio.

---

## 🤖 Modelo utilizado

Se ha entrenado un:

```
RandomForestRegressor
```

Motivos:

* Maneja bien variables categóricas codificadas
* Robusto frente a outliers
* Buen rendimiento sin necesidad de normalización

---

## 📏 Métrica de evaluación

RMSE:

```
RMSE = √(1/n * Σ(y_real - y_predicho)²)
```

Cuanto menor es el valor, mejor es el modelo.

---

## 🏆 Resultado

Primer modelo baseline:

```
RMSE ≈ 323
```

Modelo con feature engineering:

```
⬇ Mejora significativa en el score de Kaggle
```

---

## 📂 Estructura del repositorio

```
├── Laptop_Kaggle_Pipeline.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
```

---



## 👩‍💻 Autor

Proyecto desarrollado por **Pilar** como parte de su formación en **Análisis de Datos y Machine Learning**.

---


