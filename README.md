# Gas Turbine Energy Yield Prediction.
- This project aims to predict the energy yield of a gas turbine using ambient variables as features.
- It utilizes machine learning techniques, specifically neural networks, for both regression and classification tasks. 

# Dataset.
- The dataset contains 36,733 instances of 11 sensor measures aggregated over one hour from a gas turbine.
- The attributes include ambient variables such as temperature, pressure, and humidity, along with gas turbine parameters and environmental factors like carbon monoxide and nitrogen oxides levels.

# Problem Statement.
- The primary goal is to predict the turbine energy yield (TEY) using ambient variables.
- Additionally, the project involves a secondary task of classifying the turbine energy yield into two categories based on a threshold.

# Attribute Information.
- Ambient temperature (AT): Celsius
- Ambient pressure (AP): mbar
- Ambient humidity (AH): Percentage
- Air filter difference pressure (AFDP): mbar
- Gas turbine exhaust pressure (GTEP): mbar
- Turbine inlet temperature (TIT): Celsius
- Turbine after temperature (TAT): Celsius
- Compressor discharge pressure (CDP): mbar
- Turbine energy yield (TEY): MWH
- Carbon monoxide (CO): mg/m3
- Nitrogen oxides (NOx): mg/m3

# Approach.
## Data Preprocessing:
- Load the dataset and preprocess it.
- Define features and target variables for regression and classification tasks.
- Split the dataset into training and testing sets.

## Modeling:
- Utilize Multi-layer Perceptron (MLP) neural networks for both regression and classification.
- Train MLPRegressor for predicting turbine energy yield.
- Train MLPClassifier for classifying turbine energy yield based on a threshold.

## Evaluation:
- Evaluate the regression model using Mean Squared Error (MSE) and R-squared metrics.
- Evaluate the classification model using accuracy score.

# Results.
## Regression:
- Mean Squared Error (MSE): 0.33
- R-squared: 0.99
## Classification:
Accuracy: 0.94  

# Future Improvements.
- Experiment with different neural network architectures and hyperparameters.
- Explore additional feature engineering techniques.
- Investigate other machine learning algorithms for comparison.
