# Comprehensive Analysis and Multi-Output Regression Prediction Using Machine Learning and Deep Learning Models

## Project Overview

This project involves an extensive analysis and predictive modelling of a dataset with 16 input features and 3 output features. The primary goal is to perform a detailed exploratory data analysis (EDA) and implement various regression models, including machine learning and deep learning techniques, to predict the output features.

## Introduction

In this project, we aim to:
1. Analyze the given dataset to understand the relationships and distributions of the features.
2. Apply machine learning and deep learning models to predict the three output features.
3. Compare the performance of different models and identify the best approach for this multi-output regression problem.

## Dataset

The dataset consists of:
- 16 numerical input features.
- 3 numerical output features.

## Exploratory Data Analysis

The EDA process includes:
1. **Correlation Analysis**: Analyzing the correlation between different features to understand their relationships.
2. **Data Distribution**: Plotting histograms to visualize the distribution of each feature.
3. **Unique Value Analysis**: Examining the unique values in each feature to understand the variance.
4. **Regression Plots**: Creating regression plots for each feature with respect to all three output features separately.
5. **Feature Importance**: Extracting and visualizing the importance of different features in predicting the output.

## Preprocessing

The preprocessing steps involve:
1. Normalizing the input and output features using `MinMaxScaler`.
2. Creating sequences of data for time series prediction.
3. Splitting the data into training and testing sets.

## Modeling

The following models were implemented:
1. **Random Forest Regressor**
2. **XGBoost Regressor**
3. **SVM Regressor**
4. **SVR Multioutput Regressor**
5. **KNeighborsRegressor**
6. **ExtraTreesRegressor**
7. **Linear Regression**
8. **Convolutional Neural Network (CNN)**
9. **Recurrent Neural Network (RNN)**
10. **Long Short-Term Memory (LSTM) Network**

## Results

The performance of the models was evaluated using the following metrics:
- R2 Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

## Conclusion

The project demonstrated that traditional machine learning models, like XGBoost Regressor, often perform comparably to complex deep learning models on certain datasets. However, with proper tuning, deep learning models such as the LSTM network can achieve minimal error rates, as seen in this project where the LSTM model produced the lowest error, almost comparable to XGBoost. This highlights the potential of deep learning models when applied to suitable problems and optimized effectively.
