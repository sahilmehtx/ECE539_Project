# ECE539_Project
# Spotify Song Data Analysis Using Machine Learning

## Team Members
- Harsh Sahay
- Srijan Gupta
- Sahil Mehta

## Overview
In this project, we perform a comprehensive analysis of song data from Spotify to predict song popularity using machine learning techniques. Our study spans data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive model development and evaluation.

## Dataset
The dataset consists of 953 songs with various attributes and has been partitioned in an 80/20 ratio for training and testing. It is sourced from Kaggle and can be found (https://www.kaggle.com/datasets/arnavvvvv/spotify-music).

## Methodology
- **Data Preprocessing**: Involved cleaning, normalizing, and encoding of categorical variables.
- **Feature Engineering**: New features like 'artist_popularity' were created.
- **EDA**: Utilized correlation matrix and pairplot visualizations to understand variable relationships.
- **Model Development**: Developed pipelines for Linear Regression, Random Forest, and Gradient Boosting models.
- **Evaluation**: Assessed model performance using RMSE, MAE, and R-squared.

## Results
All models showed limited predictive power, with the Linear Regression model performing slightly better than the others based on RMSE in cross-validation. However, the negative R-squared values for Random Forest and Gradient Boosting indicated that these models did not predict the song popularity accurately.

## Contributions
- **Harsh Sahay**: Led the data analysis and visualization efforts.
- **Srijan Gupta**: Focused on data preprocessing and cleaning.
- **Sahil Mehta**: Implemented the machine learning models and conducted performance evaluations.
