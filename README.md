# Titanic Survival Prediction

Supervised classification predicting whether a passenger **survived the Titanic**, with a strong focus on **data cleaning and feature engineering**.

> **Author / Autor:** Hugo Benjumea Martínez · [github.com/Hben8](https://github.com/Hben8)

---

## 🇬🇧 English

### Overview
Classic end‑to‑end ML workflow on the Titanic dataset:
- **Missing‑value handling** (ages, fares, ports, etc.)
- **Encoding** of categorical variables (sex, embarked)
- **Feature engineering:** `family_size`, inferred **marital status from the name title** (Miss/Mrs/Mr…), **age groups**, and **min‑max scaled fare**
- Training and evaluation of classification models with **scikit‑learn**

### Data (included)
- `titanic_train.csv` — 1,047 passengers (with the `survived` ground truth)
- `titanic_test.csv` — 256 passengers to predict

### Tech stack
Python · pandas · NumPy · scikit‑learn · seaborn · Matplotlib

### How to run
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
jupyter notebook titanic_survival_prediction.ipynb
```

---

## 🇪🇸 Español

### Descripción
Flujo de ML de principio a fin sobre el dataset del Titanic:
- **Tratamiento de valores faltantes** (edad, tarifa, puerto, etc.)
- **Codificación** de variables categóricas (sexo, puerto de embarque)
- **Feature engineering:** `family_size`, **estado civil inferido del título del nombre** (Miss/Mrs/Mr…), **grupos de edad** y **tarifa escalada** (min‑max)
- Entrenamiento y evaluación de modelos de clasificación con **scikit‑learn**

### Datos (incluidos)
- `titanic_train.csv` — 1.047 pasajeros (con la etiqueta real `survived`)
- `titanic_test.csv` — 256 pasajeros a predecir

### Tecnologías
Python · pandas · NumPy · scikit‑learn · seaborn · Matplotlib

### Cómo ejecutarlo
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
jupyter notebook titanic_survival_prediction.ipynb
```
