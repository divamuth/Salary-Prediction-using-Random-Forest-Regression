# Salary Prediction using Random Forest Regression

## Overview
This project implements a **Random Forest Regression** model to predict employee salaries based on their years of experience. The dataset contains information about 200 employees, including their years of experience and corresponding salaries.

## Dataset Description
- **Source**: `salary data.csv`
- **Features**:
  - `employee_id`: Unique identifier for each employee
  - `experience_years`: Years of work experience
  - `salary`: Current salary in monetary units

## Project Workflow

### 1. Data Preparation
The data is loaded and prepared for modeling:
- Data is imported from `salary data.csv`.
- Features (`experience_years`) and target (`salary`) variables are separated.
- The dataset is split into training and testing subsets.

### 2. Model Implementation
A Random Forest Regressor is created and trained using the training data:
- **Model Parameters**: 100 estimators, random state set to 42.
- Predictions are made on the testing data.

### 3. Model Evaluation
Model performance is assessed using the following metrics:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared Score**

### 4. Visualization
A scatter plot compares actual vs. predicted salary values to illustrate model performance.

## Results and Insights
The Random Forest Regression model demonstrates strong predictive capabilities with high R-squared values and low RMSE. The visualization of actual vs. predicted salaries highlights the model's effectiveness in capturing the relationship between experience and salary.

## How to Use
1. Clone the repository and navigate to the project directory.
2. Ensure the following dependencies are installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Upload your dataset as `salary data.csv`.
4. Run the script in a Python environment to train the model and visualize results.

## Key Takeaways
- This project showcases a practical application of Random Forest Regression for salary prediction.
- Comprehensive data preprocessing, model evaluation, and visualization are included to ensure model reliability.
