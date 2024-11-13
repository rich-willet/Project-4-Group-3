# Project-4-Group-3

# Heart Disease Prediction with Machine Learning

This project aims to predict the likelihood of heart disease based on health indicators from a public dataset. Using machine learning techniques, we analyze key health and demographic factors that contribute to heart disease risk, helping to identify high-risk individuals and inform preventive efforts.

## Team Members
- Richard Willet
- Tennille Franklin
- Denise Miller
- Titus Muchiri

## Project Overview
Our goal is to build and evaluate machine learning models that can accurately predict heart disease risk. We explore the dataset with Logistic Regression and Random Forest models, using performance metrics like accuracy, precision, recall, and F1 score to assess model effectiveness. We also analyze feature importance to understand which health indicators most influence the risk of heart disease.

## Key Questions
1. What are the most important health indicators for predicting heart disease?
2. Can clustering techniques identify distinct groups at higher risk for heart disease?
3. If individuals with known risk factors are excluded, can heart disease still be predicted accurately?
4. How does heart disease prevalence differ between individuals with obesity and those with normal BMI?


## Dataset
The dataset used is publicly available on Kaggle: [Heart Disease Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/data). It includes health indicators such as blood pressure, BMI, smoking status, physical activity, and demographic factors.

## Methodology

### Data Preparation
- Load and clean the dataset, handling missing values as needed.
- Split the dataset into features (health indicators) and the target variable (heart disease status).

### Feature Engineering
- Standardize or normalize numerical features as necessary.
- Encode categorical features for compatibility with the machine learning models.

### Model Selection
We chose two main models:
- **Logistic Regression** for its interpretability, as it shows the impact of each indicator on heart disease risk.
- **Random Forest** for its ability to handle non-linear relationships and its robustness in identifying feature importance.

### Training and Evaluation
- Train the models on a training dataset and evaluate them using accuracy, precision, recall, and F1 score.
- Perform hyperparameter tuning with grid search to improve model performance.

### Interpretation and Visualizations
- Analyze feature importance to identify key health indicators.
- Generate visualizations, including:
  - A box plot comparing health indicators by heart disease risk
  - A scatter plot of age vs. heart disease status
  - A linear regression plot of health factors impacting heart disease

## Findings

### Logistic Regression
- **Significant Predictors**: High blood pressure, cholesterol levels, smoking history, and physical inactivity were strong predictors.
- **Demographic Trends**: Older individuals and males were at higher risk.
- **Model Insights**: The logistic regression model was interpretable, showing how each factor increased or decreased the likelihood of heart disease.

### Random Forest
- **Top Predictors**: High blood pressure, age, and BMI were the most influential indicators, as shown by feature importance scores.
- **Complex Interactions**: The model captured non-linear relationships, making it well-suited for complex health data.
- **Model Strength**: Random Forest demonstrated robustness and strong performance in balancing precision and recall.

## How to Use This Project

### Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`


