# Customer Churn Prediction

## Overview
This project analyzes telecom customer churn and builds machine learning models to predict which customers are likely to leave.  
The goal is to support customer retention by identifying high-risk customers early.

---

## Project Structure

- **01_churn_analysis_modeling.ipynb**  
  Exploratory data analysis, preprocessing, feature engineering, and machine learning model development.

- **02_mongodb_prediction_pipeline.ipynb**  
  Data ingestion, cleaning, and prediction pipeline using MongoDB, simulating a production-oriented workflow.

---

## Business Objective
Customer churn is a major challenge in subscription-based businesses.  
Instead of only maximizing accuracy, this project focuses on improving **recall for churned customers**, ensuring that high-risk customers are identified even at the cost of some false positives.

---

## Technologies & Tools
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- MongoDB (PyMongo)  
- Jupyter Notebook  

---

## Machine Learning Approach
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering and encoding  
- Handling class imbalance  
- Model training and comparison  
- Threshold tuning for improved churn detection  

---

## Models Tested
- K-Nearest Neighbors  
- Decision Tree  
- Random Forest  
- Logistic Regression  
- Gradient Boosting  
- XGBoost  

---

## Key Results
The best performing model was **XGBoost with threshold tuning**.

- Recall (churn class): ~0.82  
- Precision (churn class): ~0.46  
- Accuracy: ~0.70  

This balance allows effective identification of customers likely to churn.

---

## Key Insights
- Customers with shorter tenure are more likely to churn  
- Month-to-month contracts increase churn risk  
- Fiber optic internet users show higher churn  
- Electronic check payments correlate with higher churn  
- Customers without partners or dependents churn more frequently  

---

## Dataset
The dataset used in this project is a public telecom customer churn dataset (commonly available on platforms such as Kaggle).

---

## Author
Naomi Levy

