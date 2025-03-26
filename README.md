Project Overview

This project focuses on classifying cybersecurity threats using the CICIDS2017 dataset. Machine Learning models, including Random Forest and XGBoost, are used to detect and classify network intrusions. The notebook implements data preprocessing, feature selection, model training, evaluation, and visualization.

Requirements

To run this project, ensure you have the following installed:
Python 3.8+
Jupyter Notebook
Required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn xgboost




Dataset

Source: CICIDS2017 Dataset https://www.unb.ca/cic/datasets/ids.html

Storage: Extract all CSV files into a folder named CICIDS2017/.




How to Run the Project

Clone or Download the repository.
Place the dataset in the CICIDS2017/ folder.
Open Jupyter Notebook and run Untitled.ipynb.
Execute all cells sequentially.


Check outputs for:

Classification Reports
Confusion Matrices
Feature Importance
ROC-AUC Scores



Key Features

Handles Missing Values & Encoding Issues
Feature Engineering & Normalization
Machine Learning Model Training (Random Forest & XGBoost)
Performance Evaluation (Confusion Matrix, Precision, Recall, F1-score, Accuracy)
Multiclass ROC-AUC Score Calculation
Feature Importance Analysis



Expected Outputs

Model accuracy scores for Random Forest & XGBoost.
Confusion matrix visualizations.
ROC-AUC scores for multi-class classification.
Feature importance ranking.