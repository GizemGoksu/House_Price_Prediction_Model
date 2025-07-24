# House_Price_Prediction_Model
🏡 House Price Prediction
This project focuses on building a machine learning model to predict house prices using Random Forest and XGBoost regressors. The goal is to provide accurate price estimates based on various features such as location, area, construction year, and other property-related characteristics.

📁 Project Overview
Problem Type: Regression

Algorithms Used: Random Forest Regressor, XGBoost Regressor

Evaluation Metric: Root Mean Squared Logarithmic Error (RMSLE)

Dataset Source: [https://www.kaggle.com/datasets/prevek18/ames-housing-dataset]

📊 Features
The dataset contains several features related to housing, such as:

YearBuilt: Year the house was built

LotArea: Lot size in square feet

Neighborhood: Physical location within the city

OverallQual: Overall material and finish quality

GrLivArea: Above ground living area (sq ft)

... and many more

🧹 Data Preprocessing
Handled missing values using median imputation.

Converted categorical features to numerical using label encoding and one-hot encoding.

Applied feature selection based on feature importances from Random Forest.

Standardized evaluation using RMSLE to reduce sensitivity to large values.

🤖 Models
1. Random Forest Regressor
Tuned hyperparameters using GridSearchCV.

Achieved strong performance with minimal overfitting.

2. XGBoost Regressor
Used early stopping and learning rate tuning.

Slight overfitting observed, but produced solid predictions.
