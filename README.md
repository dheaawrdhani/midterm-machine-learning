# Midterm Machine Learning Project

## Overview
Project Ujian Tengah Semester (UTS) Machine Learning yang mencakup implementasi beberapa metode machine learning pada berbagai studi kasus, yaitu:

- Fraud Detection (Classification)
- Song Release Year Prediction (Regression)
- Customer Segmentation (Clustering)

Seluruh project dikerjakan menggunakan Google Colab dengan fokus pada proses preprocessing data, pelatihan model, evaluasi performa, hyperparameter tuning, hingga interpretasi model.

---

# Project List

## 1. Fraud Detection — Classification

### Description
Project ini bertujuan untuk membangun model machine learning yang dapat mendeteksi transaksi fraud berdasarkan data transaksi online.

### Methods & Algorithms
- Random Forest Classifier
- SMOTE (Oversampling)
- Optuna Hyperparameter Tuning
- MLflow Experiment Tracking

### Workflow
1. Data preprocessing
2. Missing value handling
3. Encoding categorical features
4. Train-test split
5. Model training
6. Model evaluation
7. SMOTE implementation
8. Hyperparameter tuning using Optuna
9. MLflow tracking
10. Model saving

### Evaluation Metrics
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### Result
- Best Recall Score: ~0.41
- Model performance improved after applying SMOTE and hyperparameter tuning.

---

## 2. Song Release Year Prediction — Regression

### Description
Project ini bertujuan untuk memprediksi tahun rilis lagu berdasarkan fitur audio menggunakan model regresi.

### Methods & Algorithms
- Random Forest Regressor
- Optuna Hyperparameter Tuning
- MLflow Experiment Tracking
- LIME Model Interpretation

### Workflow
1. Data preprocessing
2. Train-test split
3. Model training
4. Model evaluation
5. Hyperparameter tuning
6. MLflow tracking
7. Model interpretation using LIME
8. Model saving

### Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Result
- Initial R² Score: ~0.23
- Best R² Score after tuning: ~0.26

---

## 3. Customer Segmentation — Clustering

### Description
Project ini bertujuan untuk mengelompokkan customer berdasarkan perilaku penggunaan kartu kredit dan aktivitas transaksi.

### Methods & Algorithms
- K-Means Clustering
- PCA (Principal Component Analysis)

### Workflow
1. Data preprocessing
2. Missing value handling
3. Feature scaling
4. Elbow Method analysis
5. K-Means clustering
6. PCA transformation
7. Cluster evaluation
8. Cluster interpretation

### Evaluation Metric
- Silhouette Score

### Result
- Best Silhouette Score: ~0.46
- Customer berhasil dikelompokkan ke dalam beberapa segmentasi berdasarkan aktivitas transaksi.

---

# How to Navigate

- `fraud_detection.ipynb` → notebook untuk project fraud detection classification.
- `regression.ipynb` → notebook untuk project prediksi tahun rilis lagu menggunakan regression.
- `clustering.ipynb` → notebook untuk project customer segmentation menggunakan clustering.
- `README.md` → penjelasan umum repository dan ringkasan project.

Dhea Kusuma Wardhani
TK-46-G05
101032330059
