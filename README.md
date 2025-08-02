# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using various supervised learning regression models like Linear Regression, Decision Tree, Random Forest, and XGBoost. The dataset includes various features such as location, number of rooms, area, and more to estimate the target price.

---

## 📌 Project Overview

The goal is to build a robust machine learning pipeline that:

- Cleans and preprocesses the data
- Trains multiple regression models
- Evaluates model performance using error metrics
- Predicts accurate house prices for new data

---

## 📁 Dataset

- 📄 Dataset Name: `house_price.csv`
- 📌 Source: [Kaggle House Pricing Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) *(or your own cleaned dataset)*

### Key Features:

| Column           | Description                             |
|------------------|------------------------------------------|
| `bedrooms`       | Number of bedrooms                      |
| `bathrooms`      | Number of bathrooms                     |
| `sqft_living`    | Living area in square feet              |
| `floors`         | Number of floors                        |
| `waterfront`     | Waterfront property (1 = yes, 0 = no)   |
| `view`           | Quality of view                         |
| `condition`      | Overall condition (scale)               |
| `grade`          | Construction grade                      |
| `price`          | Target variable (House price)           |

---

## 🎯 Goals

- Understand which features most influence price
- Compare models like:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor
- Evaluate models using:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

---

## 📊 Exploratory Data Analysis (EDA)

Includes insights such as:

- Correlation heatmap
- Price vs Area plots
- Price trends based on bedrooms, condition, etc.
- Outlier detection and handling

---

## 🧠 ML Models Used

| Model                 | Description                                |
|----------------------|--------------------------------------------|
| Linear Regression     | Simple, interpretable baseline             |
| Decision Tree         | Non-linear decision-based prediction       |
| Random Forest         | Ensemble of decision trees                 |
| XGBoost               | Boosted gradient tree algorithm            |
