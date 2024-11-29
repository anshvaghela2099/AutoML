## Overview

This notebook leverages **H2O AutoML** to predict customer churn in the banking industry. It demonstrates how to automate machine learning workflows using H2O AutoML, including data preprocessing, feature selection, and model training. The goal is to build an accurate predictive model with minimal manual intervention.

## Dataset

The dataset used in this assignment contains the following features:

1. `CustomerID`
2. `Credit Score`
3. `Country`
4. `Gender`
5. `Age`
6. `Tenure`
7. `Balance`
8. `Product Number`
9. `Credit Card`
10. `Active Member`
11. `Estimated Salary`
12. `Churn` (Target variable)

## Key Features of the Notebook

- **Data Preprocessing**: Cleans the data and encodes categorical features for compatibility with H2O AutoML.
- **Feature Engineering**: Evaluates feature importance to optimize model performance.
- **H2O AutoML**: Automates model selection and hyperparameter tuning.
- **Evaluation**: Compares model performance using metrics like accuracy, AUC, and F1-score.

## Requirements

This notebook requires the following Python libraries:

- `h2o`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Learning Outcomes

- Understand the application of AutoML tools like H2O for predictive modeling.
- Learn how to preprocess and encode data for machine learning workflows.
- Evaluate and interpret model performance metrics.

