# Rossmann Store Sales Project
This project was based on a Kaggle competition with the following scenario:

<i>Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.</i>

In this way, the project consists of solving the problem proposed above.

The project had a total of 10 stages:

0. Imports - Contains all the libraries and functions used in the project
1. Data Description - In this step, the following sub-steps were performed:
    - Rename Columns
    - Data Dimensions
    - Data Types
    - Check NA
    - Fill out NA
    - Change Types
    - Descriptive Statistics
2. Feature Engineering - Creation of hypotheses and feature engineering 
3. Variable Filtering
4. Exploration Data Analysis - Univariate, Bivariate and Multivariate analysis
5. Data Preparation - Data Rescaling and Transformation
6. Feature Selection - Split data into training and testing dataset.
7. Machine Learning Modelling - Test and comparison of the following models:
    - Average Model
    - Linear Regression Model
    - Linear Regression Regularized Model - Lasso
    - Random Forest Regressor
    - XGBoost Regressor
8. Hyperparameter Fine Tune - Random Search for XGBoost Regressor
9. Error Translation and Interpretation - Understanding the impact of the project in Business and Machine Learning. 
10. Submission to Kaggle

The model was made for the forecast of 1115 stores. Sales are expected to be \\$283,882,432 over the next six weeks. In the worst case, sales will be \\$283,142,716 and in the best case, \\$284,622,126.

In Kaggle, submissions are evaluated on the Root Mean Square Percentage Error (RMSPE). The RMSPE from this test was 0.11872.
