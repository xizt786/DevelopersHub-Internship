# DevelopersHub Corporation - AI/ML Engineering Internship

This repository contains my completed tasks for the AI/ML Engineering 
Internship at DevelopersHub Corporation.

## Tasks Completed
- [x] Task 1: Exploring and Visualizing a Simple Dataset (Iris EDA)
- [x] Task 3: Heart Disease Prediction
- [x] Task 6: House Price Prediction

---

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective
Learn how to load, inspect, and visualize a dataset to understand 
data trends and distributions.

### Dataset Used
- **Iris Dataset** - 150 samples of iris flowers across 3 species 
(Setosa, Versicolor, Virginica) with 4 features: sepal length, 
sepal width, petal length, and petal width.

### Models Applied
- No predictive model was applied in this task.
- Focus was on Exploratory Data Analysis (EDA) using pandas, 
matplotlib, and seaborn.

### Key Results and Findings
- Dataset contains 150 rows and 5 columns with no missing values.
- Petal length and petal width are the most distinguishing features.
- Setosa is clearly separable from the other two species.
- Versicolor and Virginica show some overlap in feature distributions.
- Visualizations used: Scatter plots, Histograms, and Box plots.

---

## Task 3: Heart Disease Prediction

### Objective
Build a model to predict whether a person is at risk of heart disease 
based on their health data.

### Dataset Used
- **Heart Disease Cleveland UCI Dataset** - 297 patient records with 
13 medical features and 1 target variable (0 = No Disease, 1 = Disease).

### Models Applied
- **Logistic Regression** - Binary classification model to predict 
presence or absence of heart disease.

### Key Results and Findings
- **Accuracy:** 73.33%
- **AUC Score:** 0.84 — model correctly distinguishes sick vs healthy 
patients 84% of the time.
- **Top Predictive Features:** sex, ca (vessel blockage), thal 
(thalassemia type)
- **Confusion Matrix:** 23 True Negatives, 21 True Positives, 
7 False Negatives, 9 False Positives
- **Key Insight:** Gender and vessel blockage are stronger predictors 
of heart disease than cholesterol in this dataset.
- Visualizations used: Countplot, Boxplot, Heatmap, Confusion Matrix, 
ROC Curve, Feature Importance.

---

## Task 6: House Price Prediction

### Objective
Predict house prices using property features such as 
size, bedrooms, and location.

### Dataset Used
- **Housing Dataset** - 545 houses with 13 features 
including area, bedrooms, bathrooms, and amenities.

### Models Applied
- **Linear Regression** - Simple baseline model
- **Gradient Boosting** - More powerful ensemble model

### Key Results and Findings
- **Best Model:** Gradient Boosting
- **MAE:** 964,059 (average prediction error)
- **RMSE:** 1,301,872
- **Top Feature:** Area is by far the strongest 
  predictor of house price (0.45 importance score)
- **Key Insight:** Area, bathrooms and airconditioning 
  are the top 3 factors affecting house price. 
  Guestroom and mainroad have minimal impact.
- Gradient Boosting outperformed Linear Regression 
  on both MAE and RMSE.
