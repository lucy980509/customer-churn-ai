# Customer Churn Prediction & AI Retention Assistant
An end-to-end machine learning project for predicting customer churn and exploring AI-assisted customer retention.

## Project Overview

This project uses the IBM Telco Customer Churn dataset to build a complete machine learning workflow, from data exploration and preprocessing to model development and evaluation.

The project will later be extended with an AI retention assistant using retrieval-augmented generation (RAG), as well as cloud and data engineering components.

## Current Progress
```text
- [x] Exploratory Data Analysis (EDA)
- [x] Data cleaning
- [x] Train/test split
- [x] Categorical feature encoding
- [x] Numerical feature scaling
- [ ] Baseline model
- [ ] Machine learning model comparison
- [ ] PyTorch neural network
- [ ] RAG-based retention assistant
- [ ] PySpark / Databricks pipeline
- [ ] Azure integration
- [ ] Power BI dashboard
```

## Dataset

IBM Telco Customer Churn dataset

- 7,043 original customer records
- 21 columns
- Target variable: `Churn`
- 11 records with blank `TotalCharges` values were removed during data cleaning
- 7,032 records remain for modeling

## Repository Structure

```text
customer-churn-ai/
├── data/
│   └── raw/
│       └── Telco-Customer-Churn.csv
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
└── README.md

## Tools
Python, Pandas, NumPy, scikit-learn, Jupyter Notebook, Git
