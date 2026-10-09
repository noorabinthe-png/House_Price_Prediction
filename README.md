# House_Price_Prediction
Machine learning project to predict house prices using Python and Linear Regression.
# House Price Prediction Using Machine Learning

## Project Overview

This project uses Linear Regression to predict median house values based on housing-related features.

## Objective

To build a machine-learning model that learns from housing data and predicts house values.

## Dataset

California Housing dataset provided by Scikit-learn.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* NumPy
* Matplotlib
* Joblib

## Features Used

* Median income
* House age
* Average rooms
* Average bedrooms
* Population
* Average household occupancy
* Latitude
* Longitude

## Methodology

1. Loaded and explored the dataset.
2. Split the dataset into training and testing sets.
3. Trained a Linear Regression model.
4. Evaluated predictions using MAE, MSE, RMSE and R² score.
5. Compared actual and predicted house values using a graph.
6. Saved the trained model using Joblib.

## Project Files

* `House_Price_Prediction.ipynb` — notebook containing the code and results.
* `house_price_model.pkl` — saved trained model.
* `actual_vs_predicted.png` — actual-versus-predicted graph.

## How to Run

Open the notebook in Google Colab or Jupyter Notebook and run the code cells in order. Install the required Python libraries if they are not already available.

## Limitations

The predictions are based on the California Housing dataset. They should not be treated as current market prices or used directly to value properties in other locations.

## Conclusion

This project demonstrates how Linear Regression can be used to predict housing values and evaluate prediction errors.
