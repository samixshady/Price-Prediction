🏠 **Housing Price Prediction System**
A machine learning regression project that predicts California housing prices using multiple models and comparative performance analysis.

**Project Overview**
This project builds an end-to-end machine learning pipeline to predict the median house value based on socioeconomic and geographic features from the California Housing dataset (1990 Census).
The goal is to evaluate and compare different regression models to determine the most accurate and generalizable solution.

**Dataset Information**
Source: Kaggle – California Housing Prices
Rows: 20,641
Features: 10
Target Variable: median_house_value
Problem Type: Supervised Regression

**Key Features:**
Location (longitude, latitude)
Median income
Housing age
Population & households
Total rooms & bedrooms
Ocean proximity (categorical)

**Data Preprocessing**
Handled missing values using median imputation
Applied One-Hot Encoding to categorical features
Performed feature scaling (Z-score standardization)
Split dataset into 70% training / 30% testing

**Models Implemented**
Decision Tree Regressor
Linear Regression
Ridge & LASSO Regression
Support Vector Regression (SVR)

**Model Evaluation**
Models were evaluated using: R² Score, Mean Squared Error (MSE), Mean Absolute Percentage Error (MAPE), Cross-validation

**Best Performing Model: SVR**
Support Vector Regression achieved the highest R² score and demonstrated the strongest generalization capability across training and testing data.

**Technologies Used**
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook

**Key Skills Demonstrated**
Data preprocessing & feature engineering, Regression modeling, Overfitting detection

Model comparison & validation

End-to-end ML workflow implementation
