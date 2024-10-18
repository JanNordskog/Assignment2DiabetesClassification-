# Diabetes Prediction Using Machine Learning

## Project Overview

This project aims to predict whether an individual has diabetes based on their responses to the CDC's Behavioral Risk Factor Surveillance System (BRFSS) survey. The dataset includes health-related questions covering risk behaviors, chronic health conditions, and the use of preventive services. We use this data to build machine learning models that classify individuals as diabetic or non-diabetic. The project also explores the most predictive risk factors and evaluates the performance of different models.

## Dataset

- **Source**: The dataset used is `diabetes_binary_classification_data.csv`, which contains 253,680 records and 21 features.
- **Target Variable**: `Diabetes_binary` (0: no diabetes, 1: prediabetes or diabetes)
- **Features**: Includes variables such as BMI, High Blood Pressure, Cholesterol Levels, Smoking Status, Physical Activity, and more.

## Research Questions

1. Can survey questions asked by the CDC provide accurate predictions of whether an individual has diabetes?
2. What risk factors are most predictive of diabetes risk?
3. Can we use a subset of the risk factors to accurately predict whether an individual has diabetes?
4. What machine learning models are best for classifying diabetes? Compare models based on the confusion matrix and false negatives.

## Methodology

## Requirements

- Python 3.x
- Libraries:
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `seaborn`
    - `scikit-learn`

Install the required libraries using:
```bash
pip install -r requirements.txt
