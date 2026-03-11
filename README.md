# Car Price Prediction using Machine Learning

## Objective
Build a machine learning model to predict the selling price of used cars based on features like mileage, fuel type, car age, and showroom price.

## Dataset
The dataset originally had 301 entries. After cleaning and removing non-car vehicles, the final dataset contains 213 records.

## Features
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner
- Year

## Data Processing
- Removed duplicates
- Created **No_of_Years** feature
- Extracted **Brand** from car name
- Applied **One-Hot Encoding**

## Model Used
Random Forest Regressor

## Model Performance
- MAE: 0.76 Lakhs
- RMSE: 1.47 Lakhs
- R² Score: 0.69

## Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
