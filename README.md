# Rain Prediction using Machine Learning

This project analyzes meteorological data from a weather station in Niterói, Brazil, to develop a machine learning model capable of predicting rainfall based on various weather features.

## Project Overview

The dataset contains weather-related measurements such as temperature, humidity, wind speed, and atmospheric pressure. The objective was to explore the data, identify patterns, and train predictive models to classify whether or not it will rain.

## Methodology

### Data Preprocessing:

- Cleaning and handling missing values.

- Feature selection and engineering.

- Balancing the dataset using SMOTE to handle class imbalance.

### Model Selection and Training:

Compared three models:

- Random Forest

- Gradient Boosting

- Logistic Regression

Evaluated performance using accuracy, precision, recall, and F1-score.

### Hyperparameter Tuning:

GridSearchCV was used to optimize the best-performing model (Random Forest)

### Results

Random Forest (Before Tuning):

Accuracy: 95.28%

High precision and recall for both classes.

Random Forest (After Tuning):

Best hyperparameters: {'bootstrap': False, 'max_depth': 20, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 100}

Accuracy: 95.00%

Similar performance to the untuned version, indicating strong baseline results.

