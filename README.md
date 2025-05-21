# 🏡 Ames House Price Prediction with Linear Regression

This project builds a **linear regression model** to predict house prices using the **Ames Housing dataset**. Through comprehensive exploratory data analysis (EDA) and feature engineering, the model provides insights into the factors influencing residential property prices.

---

## 📈 Overview

### 🎯 Objective
- Understand key drivers of home prices.
- Use linear regression for price prediction.
- Apply EDA to clean data, handle missing values, and engineer features.

---

## 🗂 Dataset

- **Source**: Ames Housing Dataset by Dean De Cock.
- **Size**: 2,930 observations, 81 features.
- **Data Span**: House sales from 2006 to 2010 in Ames, Iowa.
- **Feature Types**: 
  - 23 Nominal
  - 23 Ordinal
  - 14 Discrete
  - 20 Continuous

---

## 🧠 Domain Insights

- **Seasonality**: Home prices peak during **summer**, both in value and volume.
- **Economic Factors**: Sales dipped in 2008 due to the financial crisis but recovered in following years.
- **Buyer Preferences**: Features like **basements**, **fireplaces**, and good **neighborhoods** positively impact prices.

---

## 🧹 EDA Highlights

- **Missing Values** handled appropriately using domain knowledge.
- **Skewness** observed in `SalePrice` and `GrLivArea`.
- **Outliers** in living area and price identified and reviewed.
- **Correlation Matrix** used to identify top predictive features.

---

## 🧪 Model

### 🔧 Approach
- Linear Regression using R.
- Evaluated with:
  - R² Score
  - Root Mean Squared Error (RMSE)

### 🧮 Feature Engineering
- Created new categorical features like `Season` from `Month`.
- Converted categorical variables using encoding.

### 📊 Results
- Final model shows a robust fit to the data.
- Good performance considering the linear model's simplicity and interpretability.

---

## 🛠 Tools & Libraries

- **R** (ggplot2, dplyr, tidyr, readr)
- RMarkdown for reproducible analysis
- Visualizations for trends and patterns

---
