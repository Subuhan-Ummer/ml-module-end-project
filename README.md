# ml-module-end-project

# Car Price Prediction

This project focuses on predicting car prices using various machine learning models. The dataset used contains car attributes, and the goal is to identify key features influencing car prices and build models to make accurate predictions.

## 🚀 Project Overview
- **Dataset:** Car Price Dataset
- **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Optuna
- **Models Used:**
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Support Vector Regressor

## 📊 Dataset Description
- **Source:** CarPrice_Assignment.csv
- **Key Features:**
  - Company Name
  - Car Length, Width, Height
  - Engine Size, Horsepower
  - Fuel System, Curb Weight
  - Price (Target Variable)

## 🔍 Exploratory Data Analysis (EDA)
- Data Cleaning (handling missing values, correcting typos)
- Feature Engineering (extracting company names, encoding categorical variables)
- Data Visualization (distribution plots, correlation heatmaps, scatter plots)

## 🧠 Model Implementation
- Data Splitting: 80% training, 20% testing
- Feature Scaling using StandardScaler
- Model Training with different regression models
- Model Evaluation Metrics:
  - R² Score
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

## 🔑 Feature Importance
- Identified top features influencing car prices using:
  - Random Forest Feature Importance
  - Recursive Feature Elimination (RFE)
  - SelectKBest with mutual_info_regression

## ⚙️ Hyperparameter Tuning
- Performed hyperparameter tuning using Optuna
- Optimized models showed significant performance improvement

## 🏆 Best Performing Model
- **Model:** Random Forest Regressor (Optimized with Optuna)
- **Performance:**
  - **Optimized R² Score:** 0.9566
  - **Optimized MSE:** 3,422,998.40
  - **Optimized MAE:** 1,287.83

## 📦 Installation
```bash
pip install numpy pandas matplotlib seaborn scikit-learn optuna
```




