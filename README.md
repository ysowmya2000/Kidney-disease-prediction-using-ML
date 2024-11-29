# Kidney-disease-prediction-using-ML
This repository contains a comprehensive pipeline for predicting kidney disease using machine learning models. The project demonstrates data preprocessing, exploratory data analysis (EDA), feature engineering, and model building with hyperparameter tuning. It evaluates multiple machine learning models for their accuracy and ROC-AUC performance.

## Libraries Used 
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

## Pipeline Overview
The project consists of the following steps:
### 1.Data Cleaning:
- Handle missing values using random sampling and mode imputation.
- Replace inconsistent and erroneous values.
- Convert categorical variables to numerical ones using label encoding.

### 2. Exploratory Data Analysis (EDA):
- Univariate analysis using histograms and count plots.
- Bivariate analysis using violin plots, KDEs, and scatter plots.
- Correlation matrix and heatmap for feature relationships.

### 3. Model Development:
- Train-test split (80%-20%).
- Models implemented:
  - Decision Tree Classifier
  - Random Forest Classifier
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Gradient Boosting Classifier
- Hyperparameter tuning using GridSearchCV.

### 4. Evaluation:
- Performance metrics: Accuracy, Confusion Matrix, ROC-AUC score.
- Comparison of models based on accuracy and ROC-AUC.

### 5. Model Deployment:
- Save the best-performing model using pickle for future use.

- Best Model: GBDT 
- ROC-AUC Score: Random Forest

### Dataset
https://www.kaggle.com/datasets/akshayksingh/kidney-disease-dataset
