# Lead Classification using Machine Learning
Project Overview
Project ID: PRCL_0019
Organization: FicZon Inc.
Problem Domain: Sales Optimization / Lead Scoring

FicZon Inc., a provider of on-premises and SaaS-based IT solutions, is experiencing a decline in sales performance due to heightened market competition. The existing method for classifying sales leads is manual and reactive, resulting in inefficiencies and missed opportunities.

This project focuses on building a Machine Learning (ML) solution to automate the classification of sales leads into High Potential and Low Potential categories. The goal is to empower FicZon’s sales team with predictive insights that enhance decision-making and improve engagement strategies.

Objectives
Data Exploration: Analyze and understand the patterns and features that influence lead conversion success.

Model Development: Train and evaluate machine learning models to predict lead quality.

Automation: Enable real-time classification of leads to support proactive sales efforts.

Dataset
The dataset was initially sourced from a MySQL database and later converted to a CSV format for modeling purposes. It contains features such as:

Lead demographics and engagement metrics

Product interests

Historical interaction data

Sales conversion outcomes

Technologies Used
Python: Data analysis and modeling

Jupyter Notebook: Development environment

Pandas, NumPy: Data manipulation

Matplotlib, Seaborn: Visualization

scikit-learn: Model training and evaluation

imblearn: Handling imbalanced classes using SMOTE

MySQL Connector: For data extraction (initial step)

Models Applied
The following models were explored and evaluated:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier

Multi-layer Perceptron (Neural Network)

Hyperparameter tuning was performed using:

GridSearchCV

RandomizedSearchCV

Evaluation Metrics
F1 Score

Classification Report

Confusion Matrix

Results
The models were compared based on their performance metrics. Techniques such as SMOTE (Synthetic Minority Oversampling Technique) were applied to handle class imbalance and improve prediction accuracy for minority classes.


