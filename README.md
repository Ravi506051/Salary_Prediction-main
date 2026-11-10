# Salary Prediction

A regression project that explores how available attributes such as experience, education and job title relate to salary estimates.

## Project workflow
- Inspect and clean the salary dataset.
- Explore salary distributions and relationships.
- Prepare numerical and categorical features.
- Train and compare regression models.
- Evaluate predictions using MAE, MSE, RMSE and R-squared.
- Review feature importance and prediction errors.

## Technology
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · GridSearchCV

## Dataset
The existing project documentation describes a dataset with 6,704 rows and six columns. Verify the current data file and its provenance before reproducing this description or sharing the data.

## Getting started
```bash
git clone https://github.com/Ravi506051/Salary_Prediction-main.git
cd Salary_Prediction-main
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
```
Open the notebook or run the entry point provided in the repository.

## Model quality
Use a held-out test set and report only measured metrics. Check for leakage, document missing-value handling and inspect residuals across experience and job categories.

## Limitations
Salary estimates depend on dataset coverage, geography, time period, currency and role definitions. They should not be treated as guaranteed compensation.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Skills Demonstrated

- Regression analysis
- feature engineering
- model comparison
- GridSearchCV
- MAE/RMSE evaluation.

## Portfolio Context

This project is part of my hands-on learning portfolio. The repository documents the workflow and implementation; results should be reproduced from the included code and data before being used in reports or professional claims.

## Regression Evaluation

- Compare a simple baseline with candidate regression models using the same data split.
- Use MAE and RMSE to describe prediction error, and R-squared as a complementary measure.
- Check residuals and subgroup errors to identify systematic under- or over-estimation.
- Salary estimates depend on dataset coverage, geography, date, and role definitions; they are not guaranteed compensation offers.
