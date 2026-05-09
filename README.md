# Exploring-if-Machine-learning-Models-can-be-used-to-detect-early-cardiovascular-risk
This project develops machine learning models to support early detection of heart disease using a large U.S. health dataset of 308,854 individuals and 19 demographic, behavioural, and clinical variables. The goal is to help healthcare professionals identify high‑risk patients earlier and guide preventive interventions.

The workflow includes data preprocessing, feature engineering, SMOTE oversampling, and probability threshold tuning to address the extreme class imbalance (≈8% positive cases). Three models were trained and evaluated — Random Forest, XGBoost, and Support Vector Machine (SVM) — with a focus on maximizing sensitivity, the most clinically important metric for early disease detection.

Embedded feature selection using importance scores from Random Forest and XGBoost identified five consistently strong predictors: general health, age category, arthritis, diabetes, and smoking history. A reduced‑feature Random Forest model achieved improved performance (balanced accuracy ≈ 75.3%, sensitivity ≈ 78.8%).

This project demonstrates how machine learning can enhance cardiovascular screening by identifying subtle risk patterns and supporting data‑driven clinical decision‑making.
