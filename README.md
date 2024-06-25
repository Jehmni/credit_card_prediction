# Credit Card Approval Prediction

## Introduction
This project aims to build a machine learning model to predict credit card approvals using logistic regression and hyperparameter optimization.

## Dataset
The dataset used for this project contains various features related to individuals applying for credit cards, including:
- Gender
- Age
- Debt
- Married
- Bank customer
- Industry
- Ethnicity
- Years employed
- Prior default
- Employed
- Credit score
- Driver's license
- Citizen
- Income
- Approved (target variable)

## Methodology
### Data Preprocessing
- Numerical features were imputed using the median and scaled.
- Categorical features were imputed using the most frequent value and one-hot encoded.

### Model Training
A logistic regression model was trained using a pipeline that incorporated preprocessing steps. Hyperparameter tuning was performed using GridSearchCV.

### Evaluation
The model was evaluated using the following metrics:
- Accuracy: 0.84
- Precision: 0.85
- Recall: 0.83
- ROC AUC: 0.84

## Conclusion
The logistic regression model performs well in predicting credit card approvals. Future work could involve exploring other models and additional feature engineering to improve performance.

## How to Run
1. Clone the repository.
2. Ensure you have the necessary libraries installed (`pandas`, `scikit-learn`).
3. Run the Jupyter notebook `ccPredict.ipynb` to see the results.
