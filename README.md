# BSNL Telecom Churn & Usage Analysis

This project analyzes telecom customer usage, churn prediction, and complaint data for BSNL. It includes data cleaning, feature engineering, model training, and prediction using decision tree and random forest classifiers.

## Project Structure

- `churn_data.csv` — Raw churn dataset (age, usage, complaints, tenure, plan type, churn label)
- `updated_churn_data.csv` — Cleaned churn dataset after imputation and encoding
- `churn_decision_tree.joblib` — Saved Decision Tree model
- `churn_random_forest.joblib` — Saved Random Forest model
- `scaler.joblib` — Scaler for feature normalization
- `telecom_raw.csv` — Raw telecom usage data
- `telecom_usage.csv` — Cleaned telecom usage data
- `cleaned_telecom_usage.csv` — Deduplicated and cleaned usage data
- `missing_telecom_usage.csv` — Usage data with missing values removed
- `complaints.csv` — Customer complaints data
- `testing3.ipynb`, `testing4.ipynb`, `testing5.ipynb`, `Untitled-1.ipynb` — Jupyter notebooks for data cleaning, feature engineering, model training, and analysis

## Main Notebooks

- [`testing4.ipynb`](d:/Project/BSNL/testing4.ipynb): End-to-end churn prediction workflow, including data cleaning, imputation, encoding, model training (Decision Tree & Random Forest), evaluation, and prediction for new customers.
- [`Untitled-1.ipynb`](d:/Project/BSNL/Untitled-1.ipynb): Telecom usage data cleaning and deduplication.
- [`testing3.ipynb`](d:/Project/BSNL/testing3.ipynb): Customer complaints data cleaning and merging.
- [`testing5.ipynb`](d:/Project/BSNL/testing5.ipynb): Example telecom data creation.

## How to Run

1. Open the notebooks in Visual Studio Code or Jupyter.
2. Run cells step by step to clean data, train models, and generate predictions.
3. Models and scalers are saved as `.joblib` files for reuse.

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- joblib

Install dependencies:
```sh
pip install pandas numpy scikit-learn matplotlib joblib
```

## Usage

- Clean and preprocess data using the provided notebooks.
- Train churn prediction models and evaluate performance.
- Use saved models to predict churn for new customers.

## License

This project is for educational and analytical purposes.
