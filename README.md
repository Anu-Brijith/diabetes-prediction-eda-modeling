# Diabetes Prediction and Exploratory Data Analysis (EDA)

This project focuses on predicting diabetes using patient health data with thorough exploratory data analysis, data preprocessing, class balancing (SMOTE), outlier treatment, and classification modeling.

##  Project Workflow

1. **EDA (Exploratory Data Analysis)**
   - Visualizations (box plots, heatmaps, distribution plots)
   - Outlier detection and treatment using capping
   - Correlation analysis and feature strength mapping

2. **Class Imbalance Correction**
   - Applied SMOTE (Synthetic Minority Oversampling Technique)

3. **Statistical Testing**
   - T-tests to validate distributions

4. **Model Building**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest Classifier

5. **Preprocessing**
   - MinMaxScaler and StandardScaler
   - Model performance comparison after scaling

6. **Feature Importance**
   - Extracted from Random Forest 

##  Models & Accuracy

| Model               | Accuracy (MinMax) | Accuracy (Standard) |
|--------------------|------------------|----------------------|
| Logistic Regression| 0.7727           | 0.7662               |
| KNN                | 0.7468           | 0.7468               |
| Random Forest      | 0.7532           | 0.7597               |

## Files Included

- `diabetes_classification_project.ipynb` – Main notebook with code and analysis
- `requirements.txt` – Required Python libraries
- `README.md` – This file

## Tools & Libraries

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

---

##  Project Objective

To explore the diabetes dataset, understand key factors influencing diabetes, and develop classification models that can effectively predict diabetes outcomes based on patient data.


