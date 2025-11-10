# Financial-Forecasting

## 📘 Overview

This project applies machine learning regression models to forecast financial sales based on various macroeconomic indicators such as GDP growth, inflation rate, unemployment rate, and market indicators.
The goal was to explore how different economic variables influence target sales and to identify the best-performing model for accurate financial forecasting.

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on financial and economic datasets.

- Build and compare regression models to predict target sales.

- Identify key economic indicators driving financial performance.

- Visualize results to improve interpretability and business insights.

## 🧰 Tools and Libraries

- Python

- Pandas, NumPy – data manipulation and computation

- Matplotlib, Seaborn – data visualization

- Scikit-learn – machine learning modeling and evaluation

## 🔍 Project Workflow
### 1. Data Preprocessing

- Loaded financial and macroeconomic data (simulated_financial_forecasting_data.csv)

- Handled missing values using KNNImputer

- Encoded categorical features using LabelEncoder

- Scaled numerical features using StandardScaler

2. Exploratory Data Analysis

- Generated distribution plots for variables such as sales, GDP growth, unemployment rate, and inflation.

- Created a correlation heatmap to identify relationships among features.

- Summarized basic statistics using describe() to understand the dataset structure.

3. Model Development

- Implemented two ensemble-based regression models:

- Random Forest Regressor – baseline model with multiple estimators for robust performance.

- Gradient Boosting Regressor – fine-tuned with learning rate adjustments for higher predictive accuracy.

4. Model Evaluation

- Models were evaluated using:

- Mean Squared Error (MSE)

- R² Score

- Explained Variance

- Median Absolute Error

- Max Error

5. Visualization

- Plotted predicted vs. actual sales values for both models.

- Compared model performance visually to determine consistency and accuracy.

## 📈 Results

Both models effectively captured the relationship between macroeconomic indicators and target sales.

Gradient Boosting Regressor showed slightly better performance due to its ability to handle non-linear relationships.

Feature importance analysis highlighted key economic factors affecting financial outcomes.

## 🧠 Skills Demonstrated

- Data Cleaning & Preprocessing

- Exploratory Data Analysis (EDA)

- Regression Modeling & Evaluation

- Feature Engineering

- Financial Data Interpretation

- Model Visualization
