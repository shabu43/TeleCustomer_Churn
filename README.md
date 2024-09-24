# Customer Churn Prediction
This repository contains a machine learning project focused on predicting customer churn for a telecom company using various supervised learning algorithms. The dataset includes customer demographics, services, and account information, which are used to build predictive models.

## Features of the Project:
## Data Preprocessing:

Handling missing values and converting categorical features to numerical ones using OneHotEncoding.
Scaling numerical features with StandardScaler.
Feature engineering and selection using statistical methods like Chi-Square Test and ANOVA.
## Feature Selection:

Chi-Square Test: Applied to categorical variables to assess their significance in predicting churn.
ANOVA (Analysis of Variance): Used for numerical features to determine their contribution to churn prediction.
Techniques for removing insignificant features and the impact on model performance.
## Models:

Logistic Regression (with Regularization: Lasso, Ridge, and ElasticNet)
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
Feature selection techniques like Recursive Feature Elimination (RFE) to improve model accuracy.
## Evaluation:

Models are evaluated using metrics like accuracy, classification report, and cross-validation to ensure robust performance.
Hyperparameter tuning using GridSearchCV to optimize model performance.
