# Customer-Churn-prediction-machine-learning-
This project predicts customer churn using a Logistic Regression Machine Learning model.
The dataset was preprocessed, analyzed through visualizations, and trained to identify whether a customer is likely to churn or not.

## Project Overview

Customer churn prediction helps businesses identify customers who may leave their services.
In this project:

-Data preprocessing was performed
-Missing values were handled
-Categorical data was encoded
-Exploratory Data Analysis (EDA) was done
-Logistic Regression model was trained
-Model performance was evaluated using multiple metrics

## Technologies Used
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Scikit-learn
-Jupyter Notebook

## Exploratory Data Analysis
-Churn Distribution

-Visualized customer churn count using countplot.

-Monthly Charges vs Churn

-Compared monthly charges of churned and non-churned customers using boxplot.

## ⚙️ Data Preprocessing
-Removed unnecessary columns (customerID)
-Converted TotalCharges into numeric format
-Filled missing values using median
-Encoded categorical variables using get_dummies()
-Standardized features using StandardScaler

## Model Training

A Logistic Regression model was trained using:

Train-Test Split: 80-20
max_iter = 1000

## Model Evaluation
Evaluation metrics used:

-Accuracy
-Precision
-Recall
-F1 Score
-Confusion Matrix
-Model Results
-Accuracy: 81.97%
-Precision: 68.30%
-Recall: 59.51%
-F1 Score: 63.61%

## 📌 Insights
-Customers with higher monthly charges are more likely to churn.
-Long-term contracts can help reduce churn.
-Better customer support may improve customer retention.
-Pricing optimization strategies can reduce churn probability.

## Visualizations Included
-Churn Distribution Plot
-Monthly Charges vs Churn Boxplot
-Confusion Matrix Heatmap

project link here-
