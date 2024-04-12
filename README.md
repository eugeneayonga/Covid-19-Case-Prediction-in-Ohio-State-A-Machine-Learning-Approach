# The Covid-19 Experience in Ohio State

## Overview
This study analyzes the level of awareness about Covid-19-related topics across Ohio counties during the pandemic. Utilizing a comprehensive dataset that includes social, economic, demographic variables alongside Covid-19 cases and deaths, this research aims to understand public engagement and awareness. The core of our analysis involved processing over 46 million tweets, identifying co-occurring hashtags, and using similarity measures to quantify discussions on Covid-19 topics.

## Methodology
The dataset was divided into a training set, accounting for 30% of the data with 3,141 observations, and a test set comprising 70% with 7,331 observations. I employed several analytical steps:

1. **Data Pre-processing**: Cleaning and preparing data for analysis.
2. **Dimensionality Reduction**: Using spectral embedding to reduce feature space while preserving essential information.
3. **Feature Selection**: Identifying significant predictors for the model.
4. **Model Training**: Implementing XGBoost’s XGBRegressor.
5. **Model Evaluation**: Fine-tuning hyperparameters to optimize performance.

## Results
The XGBoost regression model demonstrated strong predictive capability with an adjusted R^2 score of 0.9604 and an R^2 score of 0.87488 in the Kaggle competition, significantly surpassing our initial benchmark expectation of 0.5. Key findings include:

- **Model Performance**: The high R^2 scores indicate robust model effectiveness, highlighting the success of our feature engineering and modeling strategy.
- **Impact of Awareness on Covid-19 Cases**: There is a significant correlation between the level of awareness in counties and the number of reported Covid-19 cases, suggesting that higher awareness could influence case outcomes.

## Significance
The findings from this study provide valuable insights into public awareness during a health crisis, which can inform targeted public health interventions and policy-making decisions aimed at managing pandemic situations more effectively.