# Sales Prediction Using Python

This project focuses on predicting product sales using advertising data. By leveraging machine learning techniques, it explores the relationship between marketing efforts (TV, Radio, Newspaper) and resulting sales figures.

## Problem Statement

Sales prediction means predicting how much of a product people will buy based on factors such as the amount you spend to advertise your product, the segment of people you advertise for, or the platform you are advertising on about your product.

## Objective

The objective of the Sales Analysis using Python project is to understand the impact of various advertising channels—TV, Radio, and Newspaper—on product sales. Using Python libraries such as pandas, Matplotlib, Seaborn, and scikit-learn, the project involves data exploration, correlation analysis, and linear regression modeling to identify which channels contribute most to sales performance. The goal is to generate actionable insights and create a predictive model to help businesses allocate marketing budgets more effectively and maximize return on investment (ROI).

## Project Overview

The notebook performs a complete data analysis and modeling workflow:

- Exploratory Data Analysis (EDA)
- Visualizations including pairplots and boxplots
- Outlier detection and removal
- Simple Linear Regression and evaluation
- Model performance metrics (MSE, RMSE, R²)

## Tools and Technologies

- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

 ## Key Features And Vizualisations

- **Pairplot**: Analyze feature relationships visually
- **Correlation Heatmap**: Understand linear correlations between advertising channels and sales
- **Boxplot**: Detect outliers in the Newspaper variable
- **Data Cleaning**: Remove outliers using IQR method
- **Model Training**: Build and train a Linear Regression model to predict sales
- **Model Evaluation**: 
  - Visualize predicted vs. actual values
  - Calculate error metrics like MSE, RMSE, and R²

## Conclusion

In this project, we successfully built a linear regression model to predict sales based on advertising expenditures across TV, Radio, and Newspaper channels. The data was explored thoroughly using pairplots, correlation heatmaps, and boxplots to identify relationships and outliers.

After cleaning the data and training the model, we achieved strong performance metrics:
- **R² Score:** 0.899
- **RMSE:** 1.66
- **MSE:** 2.74

These results indicate that the model explains nearly **90% of the variability in sales**, making it a reliable tool for understanding how advertising investments impact outcomes. With further improvements like advanced regression techniques or cross-validation, the model could become even more robust.

This project demonstrates the power of machine learning in business decision-making and marketing optimization.

