# Sports-Performance-Analyzer

Dataset: https://www.kaggle.com/datasets/ziya07/athlete-injury-and-performance-dataset/data


## Overview

This project analyzes how various physical, training, and injury-related factors influence **athlete performance levels**.
It uses multiple machine learning models to predict performance outcomes and provides insights through exploratory data analysis (EDA) — including **gender-based performance comparison** and **feature importance interpretation**.

The dataset is sourced from [Kaggle — Athlete Injury and Performance Dataset](https://www.kaggle.com/datasets/ziya07/athlete-injury-and-performance-dataset).

---

##  Objectives

* Understand how training and injury attributes affect athletic performance.
* Compare the impact of **gender differences** on performance outcomes.
* Train and evaluate multiple ML models to classify athlete performance.
* Identify the most important factors influencing performance using feature importance.

---

## 📂 Dataset Description

The dataset contains information about:

* **Athlete demographics** (e.g., Age, Gender, BMI)
* **Training metrics** (e.g., Hours per Week, Training Intensity)
* **Injury records** (e.g., Injury Type, Injury Duration)
* **Performance Level** (target variable — categorical or numeric)

---

##  Methodology

### 1. Data Preprocessing

* Handle missing values (median for numeric, mode for categorical).
* Encode categorical variables using `LabelEncoder`.
* Scale features using `StandardScaler`.

### 2. Exploratory Data Analysis (EDA)

* Visualize correlations between training, injury, and performance features.
* Analyze **gender distribution** and **performance by gender** using boxplots and t-tests.
* Identify significant statistical differences between male and female performance.

### 3. Model Training

A variety of classification models are compared:

| Model               | Description                           |
| ------------------- | ------------------------------------- |
| Logistic Regression | Baseline linear model                 |
| SVM                 | Support Vector Machine                |
| Random Forest       | Ensemble of decision trees            |
| Gradient Boosting   | Boosted tree-based model              |
| KNN                 | k-Nearest Neighbors                   |
| Naive Bayes         | Probabilistic model                   |
| Decision Tree       | Single tree classifier                |
| AdaBoost            | Adaptive boosting classifier          |
| Extra Trees         | Randomized ensemble                   |
| XGBoost             | Gradient boosting with regularization |

### 4. Model Evaluation

Each model is evaluated on:

* Accuracy
* ROC-AUC score
* Classification report (precision, recall, F1-score)

Results are visualized through a **model comparison bar chart**.

### 5. Feature Importance

For tree-based models (Random Forest, XGBoost, etc.), feature importance is plotted to identify top predictors of performance.

---

## ⚧ Gender-Based Analysis

* **Gender distribution** visualization
* **Performance comparison** (Male vs Female)
* **Statistical testing (t-test)** for performance difference
* **Gender vs Performance Level** heatmaps and plots

This helps determine if gender plays a significant role in performance or injury-related outcomes.

---

## Outputs

* Correlation heatmap
* Gender-based boxplots and countplots
* Model comparison bar chart (accuracy and AUC)
* Feature importance plot

---

## 🏁 Results Summary

* Models are ranked by accuracy and ROC-AUC score.
* Insights on which attributes (e.g., training load, injury duration, gender) most strongly affect performance.
* Statistical evidence of whether gender differences in performance are significant.


