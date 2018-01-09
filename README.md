# Ames Housing Project
## Predicting House Price with Advanced Regression Techniques

### Project Description and Goal: 

The goal of this project is to use EDA, visualization, data cleaning, preprocesing, and  linear regression techinques to predict home prices given the features of the home, and interpret these linear models to find out what features add value to a home. 

This project and its dataset was based on a Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

**Project Details:**

Included in this repository, the ipynb folder contains 2 notebooks that shows the work I did to clean the data and built regression models to predict sale price:

- 01_Load_data_and_EDA.ipynb - this notebook shows how I loaded the data and did Exploratory Data Analysis on the dataset.
- 02_Preprocessing_and_modeling_ipynb - this notebook shows preprocessing and model creation to analyze the housing data.

**Results:**

After carefully cleaning and preprocessing the data and using regression models, I found the most important features in house sale predictions: 

Top three values that would increase value in a home: GrLivArea, OverallQual, YearBuilt

Top three values that would decrease value in a home: MSZoning_RM, SaleCondition_Family, Foundation_CBlock.