# Lumina HealthPath - Metabolic Risk Predictor

![Python](https://img.shields.io/badge/Python-3.9%2B-blue) 
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.0+-orange)
![Pandas](https://img.shields.io/badge/pandas-2.0+-blue)

**Automated binary classification model to identify High-Risk metabolic patients using wearable and clinical data.**

---

## 🏥 Business Context

**Lumina HealthPath** is a Series B HealthTech company specializing in preventative diagnostics.  
This project replaces manual Excel-based thresholding with an **interpretable Logistic Regression model** that meets strict clinical requirements:

- **Minimum Recall of 0.85** for the High-Risk class (patient safety priority)
- Full coefficient interpretability for medical auditors
- Standardized preprocessing pipeline
- Ready for AWS SageMaker deployment

---

## 📊 Project Objectives

- Perform EDA and handle missing values in medical dataset
- Train a **Logistic Regression** model with class balancing
- Optimize decision threshold to achieve **Recall ≥ 0.85**
- Provide clinical interpretability through feature coefficients
- Generate Confusion Matrix and Precision-Recall visualizations

---

## 🚀 Features

- Synthetic 50,000 patient records (realistic metabolic markers)
- Robust median imputation strategy
- Feature standardization using `StandardScaler`
- Hyperparameter-aware Logistic Regression (`class_weight='balanced'`)
- Threshold optimization for high-recall use case
- Full evaluation metrics and visualizations

---

## 📁 Project Structure
