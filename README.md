# Home Credit Default Risk Prediction

## Project Overview

This project predicts whether a customer is likely to experience payment difficulties using machine learning.

The project uses the **Home Credit** dataset and compares multiple classification algorithms to identify customers who may be at higher financial risk.

## Objectives

* Analyze customer financial and demographic data.
* Perform data cleaning and preprocessing.
* Handle missing values and categorical variables.
* Create useful features for prediction.
* Train multiple machine learning models.
* Evaluate model performance using appropriate classification metrics.
* Identify the most important features influencing predictions.
* Save the final model for future predictions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Jupyter Notebook
* Joblib

## Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest
* XGBoost

XGBoost was selected as the final model because it provided strong performance for the financial-risk classification problem.

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC

The XGBoost model achieved an ROC-AUC score of approximately **0.756**.

Because the dataset is highly imbalanced, recall, precision, F1-score and ROC-AUC were considered alongside accuracy.

## Feature Importance

The model identified several influential features, including:

* EXT_SOURCE_3
* EXT_SOURCE_2
* NAME_EDUCATION_TYPE
* NAME_INCOME_TYPE
* CODE_GENDER
* EXT_SOURCE_1
* FLAG_DOCUMENT_3
* FLAG_OWN_CAR
* AGE_YEARS

Feature importance helps explain which variables the model relied on most when making predictions.

## Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Categorical Encoding
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Feature Importance
      ↓
Final Model
      ↓
Customer Risk Prediction
```

## Project Files

```text
Home-Credit-Default-Risk-Prediction/
│
├── Home_Credit_Default_Risk_Analysis.ipynb
├── financial_risk_xgboost.pkl
├── financial_risk_scaler.pkl
└── README.md
```

## Dataset

The project uses the **Home Credit Default Risk** dataset.

The original dataset is not included in this repository because of its large size.

## Conclusion

This project demonstrates an end-to-end machine learning workflow for financial risk prediction, including data preprocessing, feature engineering, model training, evaluation, feature importance analysis, and model persistence.

The project also demonstrates how machine learning can be applied to identify customers who may have difficulty making payments.
