# Module 2 - Machine Learning

## Overview

This module focuses on applying Machine Learning algorithms to the cleaned Titanic dataset.

The main objective is to prepare the data for Machine Learning, train different models, evaluate their performance, handle class imbalance, and save the trained models.

---

## Dataset

The dataset used in this module is the cleaned Titanic dataset.

The target variable for classification is:

- `survived`

Where:

- `0` = Did not survive
- `1` = Survived

---

## Machine Learning Workflow

The following steps were performed:

1. Load the cleaned dataset
2. Select features and target
3. Train-test split
4. Encode categorical features
5. Scale numerical features
6. Train Logistic Regression
7. Train Decision Tree
8. Train Random Forest
9. Evaluate classification models
10. Handle class imbalance
11. Perform hyperparameter tuning
12. Perform regression
13. Evaluate regression model
14. Save trained models

---

## Preprocessing

### Categorical Encoding

Categorical variables were converted into numerical values using One-Hot Encoding.

```python
pd.get_dummies()
