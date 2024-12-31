# Optimization of Boosting Models on Mixed Feature Datasets with Binary Classification Targets

## Overview

This repository showcases a machine learning project focused on **binary classification**, aiming to predict a target variable based on a set of features. The dataset comprises both **numerical** and **categorical** variables, providing a diverse range of information for model training and evaluation.

## Dataset Features

The dataset includes a mix of feature types:

- **Numerical Features:**
  - Continuous variables representing measurable quantities.
  - Examples include metrics like duration, sales, commission, age, etc.

- **Categorical Features:**
  - Discrete variables representing distinct categories or classes.
  - Examples include codes for distributors, products, destinations, gender, etc.

## Task

- **Type:** **Binary Classification**
- **Objective:** Predict the **target binary variable** (`0` or `1`) based on the provided numerical and categorical features.

## Models Implemented

To achieve robust and accurate predictions, the following state-of-the-art classification models have been employed:

1. **CatBoost**
   - Excels in handling categorical features natively without extensive preprocessing.
   - Robust to missing values, allowing the model to manage incomplete data effectively.

2. **LightGBM**
   - Highly efficient and scalable, suitable for large datasets.
   - Supports native handling of categorical variables with optimized split algorithms.

3. **XGBoost**
   - Renowned for its performance and flexibility in various classification tasks.
   - Requires manual encoding of categorical variables but offers extensive hyperparameter tuning options.

## Project Structure

- **Exploratory Data Analysis (EDA):** Provides insights into feature distributions, relationships, and data quality.
- **Data Preprocessing:** Handles missing values, encodes categorical variables, and prepares data for modeling.
- **Model Training:** Implements and trains CatBoost, LightGBM, and XGBoost classifiers.
- **Evaluation:** Assesses model performance using the weighted F1 score and other relevant metrics.
- **Hyperparameter Tuning:** Optimizes model parameters to enhance predictive performance.
