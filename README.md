#Code_ALPHA
Car Price Prediction using Machine Learning 🚗💰
Project Overview

This project predicts the selling price of cars based on features like brand, year, mileage, fuel type, transmission, and more. It demonstrates a complete end-to-end machine learning workflow from data exploration to model evaluation.

Dataset

The dataset contains car-related features:

Car_Name – Model of the car

Year – Year of manufacturing

Present_Price – Original price of the car

Driven_kms – Total kilometers driven

Fuel_Type – Petrol/Diesel/CNG

Seller_Type – Dealer/Individual

Transmission – Manual/Automatic

Owner – Number of previous owners

Selling_Price – Target variable

Workflow

Exploratory Data Analysis (EDA)

Visualized distributions and relationships between features

Identified trends like newer cars and certain brands having higher resale value

Data Preprocessing & Feature Engineering

Encoded categorical variables (One-Hot Encoding)

Created new feature: Car_Age = CurrentYear - Year

Scaled numerical features for linear models

Modeling

Linear Regression (baseline)

Random Forest Regressor (non-linear model)

Hyperparameter tuning using GridSearchCV

Evaluation

Metrics: R² Score, MAE, MSE, RMSE

Linear Regression performed best (R² ≈ 0.89)

Random Forest showed slightly lower performance, indicating linear relationships dominate

Feature Importance

Car Age, Present Price, Fuel Type, and Transmission were the most influential features

Key Insights

Linear relationships dominate car price prediction in this dataset

Feature engineering (Car Age) improved predictive performance

Simple models like Linear Regression can outperform complex models on smaller datasets

Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Linear Regression, Random Forest, GridSearchCV)

How to Run

Clone this repository

Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Jupyter Notebook Carprice_Prediction.ipynb
