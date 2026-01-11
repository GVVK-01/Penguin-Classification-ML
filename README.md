# Penguin Species Classification (Machine Learning Project)

## 📌 Project Overview
This project focuses on classifying penguin species from the Palmer Archipelago dataset using machine learning models. 
The dataset contains measurements related to penguin physical characteristics such as flipper length, beak size, body mass, island, and gender.

This is a clean end-to-end ML pipeline including:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Outlier Treatment
- Feature Engineering
- Model Training & Evaluation
- Model Comparison
- Exporting Best Model

---

## 📊 Dataset Information
Dataset contains 7 features:

| Feature | Type | Description |
|---|---|---|
| species | Categorical (Target) | Penguin species (Adelie, Gentoo, Chinstrap) |
| culmen_length_mm | Continuous | Beak length (mm) |
| culmen_depth_mm | Continuous | Beak depth (mm) |
| flipper_length_mm | Continuous | Flipper length (mm) |
| body_mass_g | Continuous | Body mass (g) |
| island | Categorical | Island of habitat |
| sex | Categorical | Male/Female |

---

## 🧹 Preprocessing Steps
- Missing value handling
- Label & One-Hot encoding
- Standard Scaling
- Outlier treatment using IQR
- Train-Test split (75/25)

---

## 🤖 Models Evaluated
The following classification models were trained:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest

---

## 🏆 Model Performance

| Model | Accuracy | F1-Score |
|---|---|---|
| Logistic Regression | 0.988 | 0.986 |
| Decision Tree | 0.940 | 0.939 |
| KNN | 0.988 | 0.986 |
| SVM | 0.988 | 0.986 |
| Random Forest | **1.000** | **1.000** |

### Best Model: `Random Forest Classifier`

---

## 🗂 Results
- Random Forest achieved perfect classification
- Dataset is highly separable based on physical measurements

---

## Tech Stack

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

