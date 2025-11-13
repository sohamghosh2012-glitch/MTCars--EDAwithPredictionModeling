# EDAwithPredictionModeling
Exploratory Data Analysis and Fuel Efficiency Prediction using the MTCARS Dataset

With rising fuel costs and growing environmental concerns, understanding the factors that influence a vehicle’s fuel efficiency (miles per gallon – MPG) is crucial for automobile manufacturers, policymakers, and consumers.

This project aims to analyze the MTCARS dataset to identify key characteristics (such as weight, horsepower, number of cylinders, and transmission type) that significantly impact a car’s fuel efficiency.
Additionally, a predictive model is developed to estimate MPG based on these features, helping to uncover actionable insights that could guide design and performance improvements.

📊 Project Overview

This project involves two major components: Exploratory Data Analysis (EDA) and Predictive Modeling.

Data Exploration & Cleaning

Performed a detailed exploratory data analysis on the MTCARS dataset (32 car models, 11 features).

Examined data structure, summary statistics, and handled categorical variables.

Identified relationships between MPG and other numeric variables like weight, horsepower, and displacement.

Visual Analysis

Created correlation heatmaps, scatter plots, and boxplots to understand feature relationships.

Observed that weight (wt) and horsepower (hp) are negatively correlated with MPG, while manual transmission (am=1) cars generally show higher fuel efficiency.

Model Development

Built and evaluated a Linear Regression model to predict MPG.

Achieved an R² score of 0.747, indicating a good fit.

Then implemented a Random Forest Regressor to capture non-linear relationships, achieving improved accuracy.

Model Evaluation

Compared both models using R², MAE, and RMSE metrics.

Visualized model performance with Actual vs Predicted plots, Residual plots, and Feature Importance graphs.

🎯 Outcome

The project successfully demonstrates how different engine and design parameters affect car fuel efficiency.

The developed models can predict MPG with reasonable accuracy, providing insights that can be used to optimize vehicle design and improve fuel economy.

Further tuning and testing with advanced models or larger datasets could enhance prediction accuracy.
