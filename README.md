# Classification Algorithms for Diabetes and Loan Approval Prediction
## Overview

This project involves the implementation of machine learning models to solve classification problems using two distinct datasets. The goal is to explore, preprocess, and apply machine learning techniques to predict outcomes for diabetes diagnosis and loan approval.
## Datasets
### 1. Diabetes Classification

The dataset contains medical and lifestyle information for 10,000 individuals. The objective is to predict whether a person has diabetes, prediabetes, or does not have the condition. The target attribute is Diabetes, with three possible values: 0 (no diabetes), 1 (prediabetes), and 2 (diabetes).
### 2. Loan Approval Risk Classification

This dataset is aimed at predicting the approval status of a loan application based on various financial, demographic, and health-related attributes. The target attribute is loan_approval_status, which is binary: Approved or Declined.
### Requirements
  - Python 3.x
  - Required libraries:
   - pandas
  - numpy
  - scikit-learn
  -  matplotlib


## Exploratory Data Analysis (EDA)

Before applying any machine learning models, we conduct an Exploratory Data Analysis (EDA) to understand the distribution and nature of the attributes in both datasets. The EDA includes:

- Attribute Analysis: Identifying the types of attributes (numerical, categorical, ordinal) and their ranges.
- Class Balance Analysis: Checking the distribution of classes in the target attribute to identify any imbalance.
- Correlation Analysis: Examining the correlations between attributes to detect any redundancy.

## Data Preprocessing

The preprocessing steps include:

- Handling Missing Values: Imputing missing values using appropriate strategies (mean, median, etc.).
- Outlier Detection: Identifying and handling extreme values in numerical attributes.
- Feature Scaling: Standardizing numerical attributes to ensure consistency in model training.
- Encoding Categorical Variables: Converting categorical attributes into a numerical format suitable for machine learning models.

## Machine Learning Models

Two algorithms were implemented to solve the classification problems:

### Random Forest Classifier:
  - Implemented using both custom code and the scikit-learn library.
  - Hyperparameters include max depth, number of estimators, and the criterion for splitting.

### Multi-Layer Perceptron (MLP):
  - Implemented using both custom code and the scikit-learn library.
  - Hyperparameters include network architecture, learning rate, and activation functions.
