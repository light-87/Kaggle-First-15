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

Certainly! Below is the corrected markdown version of the README for your `DataScienceProject` class:

---

```markdown
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
   ```

2. **Data Visualization (Before Preprocessing):**
   ```python
   dsp.visualize_data(data, title_suffix='(Original)')
   ```

3. **Preprocess Data:**
   ```python
   preprocessed_data = dsp.preprocess_data(data, target_column)
   ```

4. **Data Visualization (After Preprocessing):**
   ```python
   dsp.visualize_data(preprocessed_data, title_suffix='(Preprocessed)')
   ```

5. **Run the Main Pipeline:**
   ```python
   dsp.main_pipeline(file_path, target_column)
   ```

## Methods Overview 🔍
- `load_data(file_path)`: Loads data from the specified file path 📂.
- `report_missing_values(df)`: Reports missing values and suggests imputation 📝.
- `apply_imputations(df, imputation_values)`: Applies the suggested imputations 👍.
- `visualize_data(data, title_suffix)`: Visualizes the distributions of features 📊.
- `select_data_within_iqr(df, iqr_factor)`: Filters out outliers 🚫.
- `apply_log_transformation(df, target_column, skew_threshold)`: Applies log transformation 🔄.
- `preprocess_data(data, target_column)`: Comprehensive preprocessing 🔧.
- `train_model(training_data, target_column)`: Trains a Linear Regression model 🏋️‍♂️.
- `plot_actual_vs_predicted(y_test, y_predict, model_type)`: Plots actual vs predicted values 📉.
- `plot_learning_curve_and_prediction_error(model, X_train, X_test, y_train, y_test, model_type)`: Plots learning curve and prediction error 📈.
- `feature_importance_lasso(X_train, y_train, X_test, y_test)`: Feature importance using Lasso 🔍.
- `make_prediction(model, new_data)`: Makes predictions with the trained model 🔮.
- `train_and_evaluate(X_train, X_test, y_train, y_test)`: Trains and evaluates the model 📏.
- `main_pipeline(file_path, target_column)`: The primary method to run the entire pipeline 🚦.
- `compare_with_baseline(data, target_column)`: Compares with a baseline model ⚖️.

## Requirements 📋
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `yellowbrick`
```

---
