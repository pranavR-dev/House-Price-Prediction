# House Price Prediction using Machine Learning

## Project Overview

This project predicts house prices using machine learning techniques on the California Housing Dataset.

The project includes data inspection, data cleaning, exploratory data analysis, model training, evaluation, comparison, and feature importance analysis.

## Dataset

The project uses the California Housing Dataset provided by Scikit-learn.

The dataset contains the following features:

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

The target variable is `price`, representing the median house value in units of $100,000.

## Project Workflow

1. Import required libraries
2. Load the California Housing Dataset
3. Inspect the dataset
4. Check for missing values
5. Check and remove duplicate rows
6. Perform Exploratory Data Analysis (EDA)
7. Analyze feature correlations
8. Split the data into training and testing sets
9. Train Linear Regression model
10. Train Random Forest Regressor
11. Evaluate model performance
12. Compare the models
13. Select the best-performing model
14. Analyze feature importance
15. Generate sample predictions

## Machine Learning Models

### Linear Regression

Linear Regression is used as a baseline model for predicting house prices.

The model uses `StandardScaler` through a Scikit-learn Pipeline for feature scaling.

### Random Forest Regressor

Random Forest Regressor is used to capture non-linear relationships between the input features and house prices.

The model is configured with 100 decision trees.

## Exploratory Data Analysis

The project includes:

- House price distribution
- Median income vs. house price analysis
- House age vs. house price analysis
- Correlation heatmap
- Model performance comparison
- Actual vs. predicted price visualization
- Random Forest feature importance

## Model Evaluation

The models are evaluated using the following metrics:

| Metric | Purpose |
|---|---|
| MAE | Measures average absolute prediction error |
| MSE | Measures average squared prediction error |
| RMSE | Measures the square root of MSE |
| R² Score | Measures how well the model explains the target variation |

The model with the highest R² Score is selected as the best-performing model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Structure

```text
House-Price-Prediction/
│
├── HousePricePrediction.ipynb
└── README.md
