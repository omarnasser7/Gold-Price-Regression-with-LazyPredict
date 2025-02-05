# 🌟 Gold Price Regression with LazyPredict 🌟

## 📚 Table of Contents
- [🌟 Gold Price Regression with LazyPredict 🌟]
  - [� Table of Contents](#-table-of-contents)
  - [📜 Overview](#-overview)
  - [🔍 Introduction](#-introduction)
  - [📊 Dataset](#-dataset)
  - [💻 Installation](#-installation)
  - [🔧 Workflow](#-workflow)
    - [🗂️ Data Preprocessing](#️-data-preprocessing)
    - [📈 Model Evaluation with LazyPredict](#-model-evaluation-with-lazypredict)
    - [📊 Visualization of Results](#-visualization-of-results)
    - [🏆 Choosing the Best Model](#-choosing-the-best-model)


## 📜 Overview
This notebook demonstrates how to use the `LazyPredict` library for quickly evaluating multiple regression models on the task of predicting gold prices. The notebook provides a streamlined approach to comparing the performance of different machine learning models, focusing on metrics such as **R-Squared**, **RMSE (Root Mean Squared Error)**, and **Time Taken**.



## 🔍 Introduction
Predicting gold prices is a challenging task due to the complex and volatile nature of financial markets. This notebook leverages `LazyPredict` to automatically train and evaluate a wide range of regression models, providing a quick comparison to identify the best-performing model.

## 📊 Dataset
The dataset used in this notebook is historical gold prices data. It includes features such as:
- **Date**: The date of the record.
- **Gold Price**: The price of gold on that date.
- **Various macroeconomic indicators** (e.g., oil prices, currency exchange rates).

This dataset is crucial for training regression models to predict future gold prices based on historical data.

- **Dataset Link**: [Gold Price Dataset on Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data) 🥇

## 💻 Installation
To run this notebook, you need the following Python libraries:
- `pandas` 📊
- `scikit-learn` 🔍
- `LazyPredict` ⚡
- `matplotlib` 📈
- `seaborn` 

You can install these dependencies via pip:

## 🔧 Workflow

### 🗂️ Data Preprocessing
The notebook begins by loading and preprocessing the dataset. Key steps include:
- Handling missing values. ❌
- Feature engineering. 🛠️
- Splitting the data into training and testing sets. 📉📈

### 📈 Model Evaluation with LazyPredict
`LazyPredict` is used to evaluate various regression models. This library simplifies the process of fitting multiple models and comparing their performance metrics:
- **R-Squared**: Measures how well the model explains the variance in the target variable. 📊
- **RMSE**: Indicates the average error of the model's predictions. 📉
- **Time Taken**: The computational time required to train and predict using each model. ⏱️

### 📊 Visualization of Results
The notebook includes visualizations to compare model performance:
- Bar plots for R-Squared, RMSE, and Time Taken.
- These plots help in identifying models that offer the best trade-off between accuracy and computational efficiency. 📊✨

### 🏆 Choosing the Best Model
The notebook provides a method to select the best model based on a combination of R-Squared and RMSE. The chosen model is highlighted as the "best" based on these criteria, making it suitable for predicting gold prices. 🥇

- **Notebook Link**: [Gold Price Regression with LazyPredict on Kaggle](https://www.kaggle.com/code/omarnasser7/gold-price-regression-with-lazypredict) 📜
