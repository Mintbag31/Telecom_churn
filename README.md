# Telecom_churn

A machine learning project for predicting telecom customer churn using logistic regression.

The project was completed while studying *Machine Learning Bookcamp* by Alexey Grigorev.

## Project

The dataset contains information about 7,043 customers, including their contracts, services, payment methods, tenure and monthly charges.

In this project I:

- cleaned and explored the data;
- analyzed feature importance;
- encoded categorical features;
- trained a logistic regression model;
- selected the classification threshold and regularization parameter;
- evaluated the model using cross-validation and ROC-AUC;
- saved the trained model and used it to predict churn for a new customer.

The final model achieved a ROC-AUC score of approximately **0.858** on the test set.

## Files

- `telecom.ipynb` — data analysis, model training and evaluation
- `churn_serving.ipynb` — loading the model and making predictions
- `requirements.txt` — required Python libraries

## Installation

```bash
pip install -r requirements.txt
