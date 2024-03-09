# Fraud Detection Model

### Problem Statement
This project focuses on developing a fraud detection model using historical transaction data. The goal is to predict whether a transaction is fraudulent or not, making it a binary classification problem.

### Data Imbalance
The dataset is highly imbalanced, with approximately 97.14% of transactions labeled as non-fraudulent and 2.86% labeled as fraudulent.


### Bivariate Analysis of Object Columns and Fraud
Visualizing the distribution of object columns and their relationship with the target variable "Fraud" using bar plots.

### Top Performing Algorithm
XGBoost Classifier emerged as the top-performing algorithm, providing high accuracy, precision, recall, and F1 score on both training and test sets.


### Business Insights
- Temporal Patterns: Transaction month is crucial for detecting fraudulent activity.
- Behavioral Characteristics: Features like 'IsOldDevice' and 'webSessWebBrowser' offer insights into fraudster behavior.
- Transaction Details: Attributes such as 'V6CF' and 'V3CF' play a critical role in fraud prediction.

### Model Generalization
The model demonstrates consistent performance on out-of-sample testing, indicating its ability to generalize well to unseen data.

### Getting Started
1. Clone the repository.
2. Install dependencies.
3. Explore notebooks for data analysis and model training.
4. Experiment with different algorithms and features to improve performance.

