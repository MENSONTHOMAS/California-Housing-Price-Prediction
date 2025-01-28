# California-Housing-Price-Prediction
## Overview

This project applies various regression algorithms to predict the median house prices in California based on multiple housing-related features. The dataset used is the California Housing Dataset available in the sklearn library.

## Dataset Description

The dataset consists of features that describe housing districts in California, including:
MedInc: Median income in block group
- HouseAge: Median house age in block group
- AveRooms: Average number of rooms per household
- AveBedrms: Average number of bedrooms per household
- Population: Block group population
- AveOccup: Average household occupancy
- Latitude: Latitude of block group
- Longitude: Longitude of block group

## Regression Models Used

We evaluated the following regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- AdaBoost Regressor
- MLP Regressor (Neural Network)

Key Insights

- Best Model: Random Forest Regressor (Highest R² Score: 0.83, Lowest Error Metrics)
- Worst Model: AdaBoost Regressor (Lowest R² Score: 0.56, Highest Error Metrics)
- Tree-based models (Random Forest, Gradient Boosting) performed significantly better than linear and boosting-based models
