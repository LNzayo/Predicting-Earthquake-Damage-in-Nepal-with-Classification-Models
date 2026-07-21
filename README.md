# Predicting Earthquake Damage in Nepal with Classification Models

## Overview

This project was completed as part of the **WorldQuant University Applied Data Science Lab**.

The objective is to build machine learning classification models capable of predicting whether a building suffered **severe earthquake damage** based on its structural characteristics and household information.

The project demonstrates an end-to-end machine learning workflow, including data extraction, cleaning, feature engineering, exploratory data analysis, model building, evaluation, and interpretation.

---

## Problem Statement

Following the 2015 Nepal earthquake, thousands of buildings were assessed for structural damage.

Using pre-earthquake building characteristics, the goal is to predict whether a building experienced **severe damage** (Grade 4 or Grade 5).

This type of predictive model can assist governments, NGOs, and disaster response organizations in prioritizing inspections and allocating emergency resources.

---

## Dataset

The project uses the Nepal Earthquake Damage Assessment dataset containing information on:

- Building structure
- Foundation type
- Roof type
- Floor type
- Land surface condition
- Building age
- Household characteristics
- Damage grade

The target variable was engineered into a binary classification problem:

- **0** = Not Severe Damage
- **1** = Severe Damage (Grade 4 or Grade 5)

---

## Project Workflow

- Data extraction using SQL and DuckDB
- Data cleaning and preprocessing
- Handling missing values
- Feature engineering
- Reducing high-cardinality categorical variables
- Exploratory Data Analysis (EDA)
- Feature encoding
- Train/Test split
- Baseline model evaluation
- Logistic Regression model
- Decision Tree Classifier
- Hyperparameter tuning
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
- Feature importance analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- DuckDB
- SQLite
- Scikit-learn
- Category Encoders
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall

to assess their ability to correctly identify buildings with severe earthquake damage.

---

## Key Skills Demonstrated

- Data Cleaning
- SQL Queries
- DuckDB
- Feature Engineering
- Classification
- Decision Trees
- Logistic Regression
- Model Evaluation
- Exploratory Data Analysis
- Python Programming

---

## Repository Structure

```
├── notebooks/
├── data/
├── images/
├── nepal.sqlite
├── README.md
└── requirements.txt
```

---

## Learning Outcomes

Through this project I learned how to:

- Build complete supervised machine learning pipelines
- Handle categorical variables with high cardinality
- Compare classification algorithms
- Interpret feature importance
- Evaluate classification models using multiple performance metrics
- Work with SQL databases alongside Python

---

## Acknowledgements

This project was completed as part of the **WorldQuant University Applied Data Science Lab**.
