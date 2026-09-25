Module 2 - Machine Learning
Overview
This module focuses on applying Machine Learning algorithms to the cleaned Titanic dataset.

The main objective is to prepare the data for Machine Learning, train different models, evaluate their performance, handle class imbalance, and save the trained models.

Dataset
The dataset used in this module is the cleaned Titanic dataset.

The target variable for classification is:

survived
Where:

0 = Did not survive
1 = Survived
Machine Learning Workflow
The following steps were performed:

Load the cleaned dataset
Select features and target
Train-test split
Encode categorical features
Scale numerical features
Train Logistic Regression
Train Decision Tree
Train Random Forest
Evaluate classification models
Handle class imbalance
Perform hyperparameter tuning
Perform regression
Evaluate regression model
Save trained models
Preprocessing
Categorical Encoding
Categorical variables were converted into numerical values using One-Hot Encoding.

pd.get_dummies()
