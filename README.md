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

## Dataset and workflow

`Salary_Data.csv` contains age, gender, education level, job title, years of experience, and salary. The notebook cleans missing rows, groups infrequent job titles, explores the data, encodes categorical fields, then compares linear regression, decision tree, and random forest models with a 25% test split and cross-validation.

## Run note

The notebook and `Salary Prediction.py` currently reference `C:\\Users\\acer\\Downloads\\Salary_Data.csv`. After cloning, change that path to the repository file, for example `pd.read_csv("Salary_Data.csv")`, before running. Report only metrics reproduced from the current data split; salary estimates are not guaranteed compensation.
