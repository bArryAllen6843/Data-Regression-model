# Health Insurance Cost Prediction

This project uses machine learning to predict health insurance costs based on various factors such as age, BMI, number of children, smoking status, gender, and region.

## Overview

This project implements a Linear Regression model to predict health insurance costs. It includes data cleaning, exploratory data analysis, feature engineering, model training, and validation.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- matplotlib (for visualization)


## Dataset

The project uses two CSV files:
1. `insurance.csv`: Main dataset for training the model
2. `validation_dataset.csv`: Dataset used for model validation

Both datasets contain the following features:
- age
- sex
- bmi
- children
- smoker
- region
- charges (target variable)



## Model

The project uses scikit-learn's Linear Regression model to predict insurance costs. The model is trained on the cleaned and preprocessed data from `insurance.csv` and validated using `validation_dataset.csv`.

## Results

The model predicts health insurance costs based on the input features. Detailed performance metrics and visualizations can be found in the `notebooks.ipynb` file.

---
