# Linear Regression
  ## House Price Prediction Model
  This project involves predicting house prices in California using machine learning models. The dataset includes various features such as `ocean_proximity`, `housing_median_age`, `total_rooms`, and more. The project utilizes both Linear Regression and Random Forest Regressor models to achieve a prediction accuracy of 81%.
  
  ## Introduction

This project aims to predict house prices in California using a dataset from Kaggle. The project involves Exploratory Data Analysis (EDA), feature scaling, and hyperparameter tuning to improve model performance. Both Linear Regression and Random Forest Regressor models are applied to evaluate their effectiveness in predicting house prices.

## Dataset

Link to Dataset :- [https://www.kaggle.com/datasets/camnugent/california-housing-prices](Link)

The dataset contains the following features:

- `ocean_proximity`: Categorical feature indicating the proximity to the ocean.
- `housing_median_age`: Median age of houses in the area.
- `total_rooms`: Total number of rooms in the house.
- `total_bedrooms`: Total number of bedrooms in the house.
- `population`: Population of the area.
- `households`: Number of households in the area.
- `median_income`: Median income of the residents.
and more

## Steps to Build and Deploy the House Price Prediction Model

### Step #1: Import the Required Libraries
Begin by importing essential libraries for data manipulation, analysis, and machine learning, including libraries like `numpy`, `pandas`, `scikit-learn`, and visualization tools.

### Step #2: Load the Data
Load the dataset into your working environment. This dataset will be used to train and test your predictive models.

### Step #3: Understand the Data
- **Drop Unnecessary Columns**: Remove columns that are not useful for the model to simplify the dataset.
- **Explore the Data**: Examine the dataset to understand its structure, including feature types and potential issues.

### Step #4: Data Cleaning
- **Handle Missing Values**: Identify and address missing values by either removing or imputing them.
- **Verify Unique Values**: Check the unique values in each column to ensure they are correct and consistent.
- **Feature Engineering**: Create new features or modify existing ones to enhance model performance.
- **Dimensionality Reduction**: Apply techniques to reduce the number of features if needed.
- **Outlier Removal**: Remove or adjust outliers based on domain knowledge or statistical methods if needed.
- **One-Hot Encoding**: Convert categorical variables into a numerical format suitable for modeling.

### Step #5: Build Machine Learning Models
- **Prepare Data**: Split the dataset into training and testing sets.
- **Train Models**: Fit both Linear Regression and Random Forest Regressor models to the training data.

### Step #6: Test the Models
Evaluate the performance of the models using the test data. Measure their accuracy and compare their results to determine which model performs best.

