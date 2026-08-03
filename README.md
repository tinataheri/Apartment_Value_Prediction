# Tehran Apartment Value Prediction

An exploratory machine-learning project that cleans and harmonises Tehran apartment listings from 2021 and 2023, analyses price-related factors, and evaluates how regression models generalise across years.

## Project workflow

1. Standardise column types, text values, and district labels across both datasets.
2. Identify shared districts and select comparable features.
3. Impute missing categorical and numerical values.
4. Explore feature distributions and correlations.
5. Train and tune linear, gradient-boosting, and XGBoost regression models.
6. Compare within-year performance and cross-year predictions to investigate dataset shift.

## Repository guide

| File | Purpose |
| --- | --- |
| `DS_project_cleaning.ipynb` | Cleaning, harmonisation, imputation, and feature preparation |
| `EDA.ipynb` | Exploratory analysis and visualisation |
| `Reg_Price_Pred.ipynb` | Modelling, tuning, feature importance, and cross-year evaluation |
| `data/data` | Project data asset used by the notebooks |

## Methods and tools

Python, pandas, NumPy, seaborn, matplotlib, scikit-learn, XGBoost, train/test evaluation, grid search, MAE, MSE, and feature-importance analysis.

## Running the notebooks

Install Jupyter, pandas, NumPy, matplotlib, seaborn, scikit-learn, and XGBoost. Run the notebooks in this order:

1. `DS_project_cleaning.ipynb`
2. `EDA.ipynb`
3. `Reg_Price_Pred.ipynb`

Some notebook paths may need adjustment for your local data location.

## Scope and limitations

This is an exploratory portfolio project, not a production valuation system. Listing data contains missing and inconsistent values, while market conditions differ between years. Cross-year results should be interpreted as an investigation of generalisation rather than financial advice.
