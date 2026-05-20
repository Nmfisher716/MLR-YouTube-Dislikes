## Live Project Report



# MLR-YouTube-Dislikes Individual Project
UX-focused behavioral analytics project using multiple linear regression to model YouTube audience engagement and predict video dislike patterns through interactive Quarto and Shiny-based analytics.

## Project Overview

The analysis investigates how observable YouTube engagement metrics can be used to model and predict video dislike behavior after public dislike counts became less accessible on the platform.

The project explores relationships between user engagement patterns and dislike counts using multiple regression modeling, interaction effects, transformations, and predictive diagnostics.

## Statistical Methods

- Multiple Linear Regression (MLR)
- Log-Log Regression Modeling
- Polynomial Regression
- Interaction Effects
- Box-Cox Transformation Exploration
- AIC-Based Model Selection
- Cross Validation
- RMSE Evaluation
- Residual Diagnostics

## Variables Explored

Response Variable:
- Dislikes

Predictor Variables:
- Views
- Likes
- Comment Count
- Engagement Ratios
- Polynomial Features
- Interaction Terms
- Log-Transformed Predictors

## Regression Assumptions Evaluated

- Linearity
- Homoscedasticity
- Independence
- Normality of Residuals
- Multicollinearity
- High Leverage and Influential Observations

Diagnostic tools included:
- Residual vs Fitted Plots
- QQ Plots
- Variance Inflation Factors (VIF)
- Studentized Residual Analysis

## Prediction Goals

The project focused on:
- Predicting YouTube dislike behavior
- Comparing transformed vs non-transformed models
- Evaluating predictive performance across competing regression models
- Understanding behavioral engagement relationships between audience interaction metrics

## Dataset

Kaggle Dataset Used:  
https://www.kaggle.com/datasets/datasnaek/youtube-new?select=USvideos.csv

Dataset File:
- USvideos.csv

## Academic Context

This project was completed independently using techniques and statistical foundations developed in:

- STAT 633A — Linear Regression
- California State University, East Bay

Special thanks to Dr. Kerr for providing the statistical tools and modeling foundation that supported this project.

## Author

Nicholas Fisher
