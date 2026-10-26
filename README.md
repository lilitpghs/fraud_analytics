# Fraud Risk & Review Prioritisation

## Overview
This project investigates credit card transaction data to evaluate whether a statistical model can identify labelled fraud cases more effectively than a simple transaction-amount rule. The analysis focuses on prioritising suspicious transactions when investigation capacity is limited.

## Objectives
- Examine fraud prevalence, class imbalance and data quality.
- Train a logistic regression model to identify potentially fraudulent transactions.
- Select a classification threshold for a limited review queue.
- Compare model performance with a transaction-amount baseline at equal review capacity.
- Interpret findings and recognise the limitations of the analysis.

## Dataset
The project uses the [Credit Card Fraud Detection dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download). Download the dataset and place `creditcard.csv` in the expected notebook directory before running the analysis.

## Notebook
Open `FraudLens_Project.ipynb` to explore the analytical workflow, model evaluation and comparison with the baseline approach.

## Tools
Python, pandas, scikit-learn and data visualisation.

## Limitations
The model identifies transactions associated with historical fraud labels; it does not establish fraud with certainty. Results depend on the dataset and evaluation setup, and flagged transactions require further investigation.
