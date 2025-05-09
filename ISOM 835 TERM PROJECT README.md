 ISOM 835 Term Project – Women's Safety Risk Analysis

Overview

This project analyzes data related to women's safety across various countries in 2024. The goal is to understand key factors contributing to the danger index for women and to develop predictive models to assess risk levels based on available socio-economic indicators.

Dataset

- Source: `most-dangerous-countries-for-women-2024.csv`
- Attributes include:
  - Country name
  - Women's Danger Index Total Score
  - Additional numeric and categorical features related to safety and socio-economic factors

Key Steps

1. Data Cleaning:
   - Handled missing values (imputed with means)
   - Removed duplicates
   - Standardized country names and formatting

2. Exploratory Data Analysis:
   - Summary statistics
   - Histograms of numeric features
   - Correlation heatmap

3. Data Preprocessing:
   - Feature scaling using `StandardScaler`
   - Encoding of categorical variables using `pd.get_dummies`
   - Splitting into training and test datasets

4. Modeling:
   - Trained and evaluated multiple regression models:
     - Random Forest Regressor
     - Linear Regression
   - Evaluation metrics:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)
     - R² Score

Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Install dependencies using:

bash
pip install pandas numpy matplotlib seaborn scikit-learn


How to Run

1. Open the Jupyter Notebook `ISOM_835_Term_Project_Purva_Dhuri.ipynb`
2. Run all cells in order to:
   - Load and clean the data
   - Perform EDA
   - Build and evaluate predictive models

Author

Purva Dhuri – ISOM 835 Term Project (2025)