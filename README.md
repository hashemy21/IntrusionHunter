# IntrusionHunter
ML\DL Anomaly-based Intrusion Detection System

## Overview
IntrusionHunter is an intrusion detection system that uses machine learning to detect anomalous behavior in network traffic. It is designed to be highly accurate and efficient, and uses a combination of random forest, XGBoost, CNN, and DNN for classification. The system also includes a feature selection process using random forest and performs hyperparameter tuning using Optuna.


## Dataset
The system is currently trained on the CSE-CICIDS2018 dataset, but can be easily adapted to other datasets.


## Feature Selection
The system uses random forest for feature selection which is the best method for feature selection in the anomaly based intrusion detection system.


## Hyperparameter Tuning
The system uses Optuna library for hyperparameter tuning. It finds the best hyperparameters for the classifiers used in the system.


## Classifiers
The system uses Random Forest, XGBoost, CNN, and DNN as classifiers. Each classifier is trained and tested separately and the best classifier is selected based on the performance.

## Types of Classification
IntrusionHunter performs Binary Classification (2C), Multiclass Classification (7C), Multiclass Classification (15C),

## Conclusion
IntrusionHunter is a highly accurate and efficient intrusion detection system that uses machine learning to detect anomalous behavior in network traffic. It is designed to be easily adaptable to different datasets, and includes a feature selection process and hyperparameter tuning to optimize performance.


