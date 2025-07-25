# Fraud-Transaction-Detection

## Dataset:

https://www.kaggle.com/datasets/ismetsemedov/transactions

The dataset can be downloaded from publicly available kaggle site. It is almost 2GB and cannot push to github.


## Steps to Run the Project:

1. Preprocessing

Download the dataset from the Kaggle link provided above.

### Run the "fraud_trans_pred_preprocessing.ipynb" file on the dataset.

This step performs data cleaning, feature engineering, and encoding.

After execution, it generates three processed files required for training and testing the models.

2. Model Training & Prediction

There are two main notebooks to execute:

### fraud_trans_pred_lightgbm_catboost.ipynb

Implements LightGBM and CatBoost models.


### fraud_trans_pred_xgboost_logistic.ipynb

Implements XGBoost and Logistic Regression.
