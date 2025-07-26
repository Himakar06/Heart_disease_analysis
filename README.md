# 🫀 Heart Disease Prediction - UCI Dataset

This project focuses on **exploratory data analysis (EDA)** and **predictive modeling** using the popular **Heart Disease UCI Dataset**. It aims to uncover patterns, correlations, and insights related to heart disease based on various patient attributes.


## 📌 Objectives

- Perform detailed EDA to understand feature distributions and relationships
- Clean and preprocess the dataset (handle missing values, outliers, etc.)
- Apply feature engineering techniques to improve data quality
- Visualize data insights using various plotting libraries

## 🧪 Dataset

The dataset used is the [Heart Disease UCI dataset](https://www.kaggle.com/ronitf/heart-disease-uci) containing various patient health metrics like age, cholesterol levels, resting blood pressure, etc.

## 🧹 Preprocessing Steps

- Handled missing/null values
- Encoded categorical variables (`cp`, `thal`, `slope`) using one-hot encoding
- Standardized continuous features using `StandardScaler`
- Removed potential outliers via IQR method

## 🔧 Feature Engineering

- Created interaction terms between correlated features
- Extracted high-risk indicators from composite features
- Removed irrelevant or redundant features

## 📊 Exploratory Data Analysis (EDA)

We used several visualization techniques to gain insights:

- **Histograms & KDE plots** – Distribution of numerical features (e.g., age, cholesterol)
- **Box plots** – Detect and visualize outliers
- **Correlation heatmap** – Analyze feature correlations
- **Pair plots** – Visualize pairwise relationships
- **Count plots** – Distribution of target and categorical features

### 📷 Sample Visualizations

- Age distribution with respect to heart disease
- Cholesterol levels grouped by disease status
- Correlation heatmap to identify highly related features
- Resting ECG vs. Heart Disease incidence bar plots

## 🛠️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
