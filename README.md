# Telco Customer Churn Xgboost

Telco customer churn prediction with XGBoost and SMOTE, with full EDA.

## What it does

End-to-end churn analysis: cleaning (TotalCharges fix, simplified service categories), exploratory analysis, class-imbalance handling and an XGBoost classifier.

## Files

- `telco_churn_xgboost.ipynb`

## Tools

pandas, numpy, scikit-learn, XGBoost, imbalanced-learn, Plotly, seaborn

## Dataset

IBM Telco Customer Churn dataset, 7,043 customers and 20 features, e.g. [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Test accuracy 0.78 on 1,409 customers. Churn class: precision 0.59, recall 0.59.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
