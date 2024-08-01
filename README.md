
# Car Price Prediction

## Problem Statement
The objective of this project is to develop a predictive model to estimate car prices based on various features.

<img src="dataset-cover.jpeg" >

## Dataset
The dataset contains various attributes related to cars, including:
- Year of manufacture
- Selling price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Number of previous owners
- Mileage
- Engine specifications

These features provide insights into the factors influencing car prices and can be used to build predictive models.

## Project Workflow
### 1. Data Collection
Data was sourced from Kaggle: [Car Price Prediction Dataset](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/car-price-prediction-dataset).

### 2. Data Cleaning
- Checked for and handled missing values
- Removed duplicate entries
- Analyzed data distributions and consistency
- Removed any unwanted or irrelevant values

### 3. Data Preprocessing
- Converted categorical values into numeric formats
- Transformed the data into a suitable format for modeling

### 4. Data Preparation
- Split the data into training and testing sets
- Further divided the testing set into temporary data and validation data

### 5. Model Setup
Implemented and evaluated various models, including:
- Linear Regression
- RandomForestRegressor

### 6. Performance Measurement
- RandomForestRegressor showed promising results
- Identified potential overfitting in the model

### 7. Model Fine-Tuning
- Used K-Fold Cross-Validation and GridSearchCV to identify optimal hyperparameters
- Achieved a final model accuracy of 96%

## Conclusion
The final model demonstrates a high accuracy of 96%, but there is still potential for further improvements.

Thank you for exploring this project!
