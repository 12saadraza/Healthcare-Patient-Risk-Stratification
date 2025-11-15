Overview

This project predicts high-risk patients using machine learning techniques. The goal is to support healthcare decision-making by analyzing anonymized patient data and assigning risk categories (low, medium, high).

Dataset:

1. Source: UCI Diabetes Readmission Dataset
2. Size: 5,000+ anonymized patient records
3. Contains demographics, diagnoses, admission details, lab procedures, medications, and outcomes.

Objectives:

1. Clean and preprocess patient health data.
2. Train a classification model for risk prediction.
3. Generate risk categories based on predicted probabilities.
4. Create visualizations to support clinical interpretation.

Tasks Performed
1. Data Cleaning

 .Handled missing values using mode/median imputation.
 .Encoded categorical variables.
 .Merged datasets with mapping files (admission type, discharge disposition, admission source).
 .Ensured all records followed privacy-safe standards.

2. Risk Prediction Model

 .Used Gradient Boosting Classifier for prediction.
 .Performed 80/20 train–test split.
 .Target goal: AUC > 0.85.
 .Computed predicted probabilities and assigned risk groups.

3. Visualization & Analysis

 .Created graphs for risk distribution and feature importance.
 .Used Matplotlib for clear, clinical-friendly visuals.
 .Interpreted model behavior to understand key health features.

Deliverables

 .Preprocessing notebook
 .Risk prediction model script
 .Visualizations (PNG/plots)
 .Dataset with assigned risk categories
 .Final report 
 .Presentation slides 


