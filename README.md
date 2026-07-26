# Telecom Customer Churn Prediction

A machine learning project for predicting telecom customer churn using logistic regression.

The project was completed while studying *Machine Learning Bookcamp* by Alexey Grigorev.

## Project

The dataset contains information about 7,043 telecom customers, including their contracts, services, payment methods, tenure and monthly charges.

In this project I:

- cleaned and explored the data;
- analyzed feature importance;
- encoded categorical features;
- trained a logistic regression model;
- selected the classification threshold;
- selected the regularization parameter using cross-validation;
- evaluated the model using ROC-AUC, precision, recall and a confusion matrix;
- saved the trained model and used it to predict churn for a new customer.

The final model achieved a ROC-AUC score of approximately **0.858** on the test set.

## Files

- `telecom.ipynb` — data analysis, feature preparation, model training and evaluation
- `churn_serving.ipynb` — loading the saved model and making predictions
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — project dataset
- `requirements.txt` — required Python libraries

## Installation and Running

Clone the repository:

```bash
git clone https://github.com/Mintbag31/Telecom_churn.git
cd Telecom_churn
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
python -m jupyter notebook
```

Open `telecom.ipynb` and run all cells to train and save the model.

After that, open `churn_serving.ipynb` and run all cells to load the saved model and make a prediction for a new customer.

## Environment

The project was tested with:

- Python 3.13
- pandas 2.3.0
- NumPy 2.2.6
- scikit-learn 1.7.1
- Matplotlib 3.10.3
- seaborn 0.13.2
- Jupyter 1.1.1
