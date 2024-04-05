# Flight Data Analysis

Developed by: Rehan Nasir, Aditya Shah, Aryan Chaudhary, Jhomar Gharbarran

## Introduction

Air travel is a complex industry influenced by various factors. This project utilizes machine learning techniques to analyze flight data and identify key factors affecting flight prices.

## Libraries

The code is written in Python and uses the following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The dataset used in this project is a modified dataset from [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data).

## Code Overview

The code is organized into the following sections:

1. **Data Loading and Exploration**: The dataset is loaded into a Pandas DataFrame, and exploratory data analysis (EDA) is performed to understand the distribution and relationships between different variables.

2. **Data Preprocessing**: The dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features.

3. **Model Training**: Three regression models - Linear Regression, Elastic Net, and Random Forest Regression - are trained on the preprocessed data to predict flight prices.

4. **Model Evaluation**: The performance of each model is evaluated using metrics such as \( R^2 \) score, mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).

5. **Results Visualization**: Visualizations such as bar plots, line plots, and scatter plots are generated to visualize the relationships between different variables and the model predictions.


