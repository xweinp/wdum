# WDUM

Solutions for the WDUM course at the University of Warsaw, 2025/2026.

## Assignments

| # | Topic | What's inside |
|---|-------|---------------|
| [wdum1](wdum1/) | EDA, clustering, and classification on earnings data | Data description of `earnings.csv`, distribution analysis, clustering pipeline (feature filtering, log transform, scaling, silhouette-based KMeans selection, t-SNE visualization), and a Random Forest classification model for predicting higher education with cross-validation and feature importance plots. |
| [wdum2](wdum2/) | Baselines and advanced models for classification and regression | Baseline Logistic/Linear Regression models, advanced XGBoost classification with feature selection and Optuna tuning, and advanced regression with Lasso-based feature selection plus AdaBoost (Ridge estimator) tuned with Optuna. Includes a validation helper for external validation data. |

Main work for each assignment is in `notebook.ipynb` in the respective folder.

## Quick start

Install dependencies (example with `pip`):

```bash
python -m pip install pandas numpy scipy scikit-learn matplotlib plotly tqdm xgboost optuna
```

Open a notebook:

```bash
cd wdum1
jupyter notebook notebook.ipynb
```

or:

```bash
cd wdum2
jupyter notebook notebook.ipynb
```
