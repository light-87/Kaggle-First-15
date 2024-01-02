# DataScienceProject Class 🚀

## Overview 📖
The `DataScienceProject` class is a comprehensive toolkit 🧰 designed for data science projects. It facilitates data loading 📂, preprocessing 🔧, visualization 📊, model training 🏋️‍♂️, evaluation 📏, and comparison. This class handles both numerical 🔢 and categorical 🔤 data and includes features for imputation, outlier handling, log transformation, and visualization of data distributions.

## Features 🌟
- **Data Loading:** Load data using Pandas 🐼.
- **Missing Value Report and Imputation:** Identify and impute missing values in the dataset 🧩.
- **Data Visualization:** Visualize distributions of both numerical 🔢 and categorical 🔤 features.
- **Outlier Detection:** Remove outliers based on the Interquartile Range (IQR) 📈.
- **Log Transformation:** Apply log transformation to skewed numerical features ➗.
- **Model Training and Evaluation:**
  - Linear Regression for prediction 📈.
  - Lasso Regression for feature importance analysis 📉.
- **Visualization of Model Performance:** Plot actual vs. predicted values, learning curves, and prediction errors 📊.
- **Baseline Comparison:** Compare the main model with a baseline model ⚖️.
- **Utilization of Yellowbrick for Advanced Visualizations 🎨.**

## Usage 🛠️
1. **Load Data:**
   ```python
   file_path = 'path/to/your/data.csv'
   target_column = 'YourTargetColumn'
   dsp = DataScienceProject()
   data = dsp.load_data(file_path)
