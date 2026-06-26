# Employee Attrition Prediction using Machine Learning

## Project Overview

Employee attrition prediction helps organizations identify employees who are likely to leave the company. This project uses machine learning techniques to analyze HR data and predict employee attrition based on factors such as job satisfaction, salary, work-life balance, years at the company, overtime, and performance ratings.

## Dataset

**Dataset Name:** IBM HR Analytics Employee Attrition Dataset

**Source:** Kaggle

**File Used:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`

## Objectives

* Load and explore employee data.
* Clean and preprocess the dataset.
* Analyze patterns related to employee attrition.
* Build and compare multiple classification models.
* Identify the most important factors influencing employee turnover.
* Provide actionable recommendations for HR teams.

## Technologies Used

* Python 3.x
* Jupyter Notebook / Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Project Structure

```text
EmployeeAttrition_HariKeerthana/

├── analysis.ipynb
├── HR_Attrition.csv
├── summary.pdf
└── charts/
    ├── department.png
    ├── income_attrition.png
    ├── cm.png
    ├── importance.png
    ├── wlb.png
    ├── years_company.png
    └── roc.png
```

## Models Used

### Logistic Regression

A simple and interpretable baseline model for attrition prediction.

### Random Forest Classifier

An ensemble model capable of capturing complex relationships between features.

### Gradient Boosting Classifier

A boosting-based model that improves prediction performance by combining multiple weak learners.

## Evaluation Metrics

* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

## Visualizations

* Attrition Rate by Department
* Monthly Income vs Attrition
* Confusion Matrix Heatmap
* Top 10 Feature Importances
* ROC Curve Comparison

## Key Findings

Overtime, job satisfaction, monthly income, years at the company, and job role were among the strongest factors influencing employee attrition. Employees with poor work-life balance and frequent overtime showed a higher likelihood of leaving the organization.

## Recommendations

Organizations should improve work-life balance policies, conduct regular retention discussions, and focus on employees working excessive overtime. Employee engagement initiatives and career growth opportunities can also help reduce attrition.

## Author

Hari Keerthana
