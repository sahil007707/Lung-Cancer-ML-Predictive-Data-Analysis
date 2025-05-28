# Lung-Cancer-ML-Predictive-Data-Analysis

# 🩺 Lung Cancer Risk Prediction & Analysis

![Lung Cancer Analysis Banner](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)  
> A data-driven exploration of behavioral and physiological factors contributing to lung cancer, with predictive modeling using Random Forest.

---

## 📌 Project Description

This project focuses on analyzing a **lung cancer survey dataset** to extract key insights about the patterns associated with lung cancer and develop a **machine learning model** to predict the risk based on individual survey responses.

---

## 🧪 Dataset Information

- **Records:** 309 individuals
- **Target Variable:** `LUNG_CANCER` (Yes/No, encoded)
- **Features:**
  - Demographics: Age, Gender
  - Habits: Smoking, Alcohol Consuming
  - Mental/Physical Health: Anxiety, Fatigue, Shortness of Breath, Chest Pain, etc.

---

## 📊 Exploratory Data Analysis (EDA)

### Key Visualizations
- 🔥 Correlation heatmap
- 📊 Bar plots showing age by smoking, alcohol consumption, and gender
- 🧠 Analysis of anxiety, peer pressure, and chest pain by gender
- 📈 Histogram of age frequency
- 📌 Subplots comparing symptoms across age and gender

---

## 🧠 Machine Learning

### 🔧 Preprocessing
- Label encoding for `LUNG_CANCER`
- Verified all features were numeric (`int64`)
- Train-test split (80/20)

### 📦 Model Used
- **Random Forest Classifier**

### 🧪 Evaluation
- Confusion Matrix
- Classification Report
- Feature Importance Plot

### ✅ Top Predictive Features
- Smoking
- Chronic Disease
- Shortness of Breath
- Chest Pain
- Peer Pressure

---

## 📁 Project Structure
📦 lung-cancer-analysis/
├── 📊 lung_cancer_analysis.ipynb # Jupyter notebook with full EDA & ML
├── 📈 figures/ # Saved plots and charts
├── 📄 README.md # Project documentation
└── 📂 dataset/
└── survey_lung_cancer.csv # Dataset

