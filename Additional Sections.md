## Executive Summary

Following the devastating 2015 Nepal Earthquake, accurately identifying buildings at risk of severe structural damage is essential for emergency response and disaster preparedness.

This project applies supervised machine learning techniques to predict severe building damage using pre-earthquake structural characteristics. 
Two classification algorithms—Logistic Regression and Decision Tree Classifier were developed, evaluated, and compared to understand the factors influencing earthquake resilience.

## Business Problem

Disaster response teams have limited resources immediately after an earthquake.

Being able to predict which buildings are most likely to experience severe damage allows governments and humanitarian organizations to:

- Prioritize inspections
- Allocate emergency resources
- Reduce response times
- Improve disaster preparedness

- ## Research Questions

This project seeks to answer:

- Which building characteristics best predict severe earthquake damage?
- Does building age significantly affect structural resilience?
- Which foundation types perform best during earthquakes?
- Can machine learning accurately classify damaged buildings?
- Which classification model performs better?

## Key Variables

| Feature | Description |
|----------|-------------|
| age_building | Age of building |
| foundation_type | Foundation construction type |
| roof_type | Roof material |
| ground_floor_type | Ground floor construction |
| other_floor_type | Upper floor construction |
| position | Building position |
| plan_configuration | Structural layout |
| superstructure | Primary construction material |
| severe_damage | Target variable (0 = No, 1 = Yes) |

## Feature Engineering

Several preprocessing steps were performed:

- Created binary target variable (`severe_damage`)
- Removed data leakage variables
- Reduced high-cardinality caste categories
- Encoded categorical variables
- Split data into training and testing datasets

## Data Quality Assessment

The dataset was examined for:

- Missing values
- Duplicate observations
- High-cardinality features
- Class imbalance
- Data leakage
- Invalid values

## Data Pipeline

SQLite Database
        ↓
DuckDB SQL Queries
        ↓
Pandas DataFrame
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Encoding
        ↓
Machine Learning
        ↓
Evaluation

## Model Comparison

| Model | Advantages |
|--------|------------|
| Logistic Regression | Simple, interpretable baseline model |
| Decision Tree | Captures nonlinear relationships and interactions |

## Why Accuracy Is Not Enough

This project evaluates models using multiple metrics:

### Accuracy
Overall percentage of correct predictions.

### Precision
Of all buildings predicted to have severe damage, how many actually did?

### Recall
Of all buildings that truly suffered severe damage, how many were correctly identified?

These metrics provide a more complete assessment of classification performance.

## Feature Importance

Decision Tree feature importance analysis identified the structural characteristics most strongly associated with severe earthquake damage.

This analysis provides interpretable insights for disaster risk reduction and infrastructure planning.

## Challenges

Some challenges encountered during the project included:

- High-cardinality categorical variables
- Missing values
- Preventing data leakage
- Handling unseen categories
- Model overfitting
- Hyperparameter tuning

## Ethical Considerations

Machine learning models should support—not replace—engineering inspections.

Predictions should be used to prioritize inspections rather than make final safety decisions.

## Potential Impact

Predictive models like this can assist:

- Governments
- Disaster management agencies
- NGOs
- Civil engineers
- Urban planners

by enabling data-driven disaster response and preparedness.

## What I Learned

Throughout this project I gained hands-on experience with:

- SQL for data extraction
- DuckDB analytics
- Data wrangling
- Feature engineering
- Exploratory data analysis
- Classification algorithms
- Model evaluation
- Hyperparameter tuning
- Interpreting feature importance

## Repository Highlights

✔ End-to-end Machine Learning Pipeline

✔ SQL + DuckDB Data Extraction

✔ Feature Engineering

✔ Logistic Regression

✔ Decision Tree Classification

✔ Model Evaluation

✔ Feature Importance Analysis

✔ Professional Documentation

