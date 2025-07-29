
# House Price Prediction in Riyadh

This project focuses on predicting house prices in Riyadh, Saudi Arabia using various machine learning techniques. The dataset contains features like area, number of rooms, parking availability, and address location to estimate property prices.

## Features

- Data cleaning and preprocessing
- Exploratory data analysis
- Multiple machine learning models:
  - Linear Regression
  - Polynomial Regression
  - Random Forest
  - XGBoost
- Feature engineering
- Outlier detection
- Model evaluation metrics

## Dataset

The dataset `housePrice_riyel.csv` contains the following columns:
- Area: Size of the property (in square meters)
- Room: Number of rooms
- Parking: Parking availability (1 for yes, 0 for no)
- Address: Location of the property
- Price: Price in Saudi Riyals
- Price(USD): Price in US Dollars (converted)

## Data Preprocessing

1. Handling missing values
2. Cleaning numeric columns (removing commas)
3. Converting data types
4. Removing outliers
5. Feature engineering:
   - Address encoding using mean prices
   - Creating new features (Area_per_Room, Parking_Ratio)
6. Standard scaling for numerical features

## Models Implemented

1. **Linear Regression**
   - Basic linear model
   - MAE and R² evaluation metrics

2. **Polynomial Regression (degree=2)**
   - Captures non-linear relationships

3. **Random Forest Regressor**
   - Ensemble method with 100 trees

4. **XGBoost Regressor**
   - Gradient boosting with 100 estimators


## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
