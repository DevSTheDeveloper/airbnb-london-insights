# Airbnb London Price Prediction

## Overview

This project builds a machine learning model to predict Airbnb listing prices in London. Using a dataset of listings with features like room type, location, host details, and availability, the model estimates nightly prices for listings.

## Features Used

- Room type (encoded)
- Minimum nights
- Number of reviews
- Reviews per month
- Calculated host listings count
- Availability (days per year)
- Latitude and longitude (with zonal encoding)
- Borough weight (a score representing average house prices by borough)

## Model

A Random Forest Regressor is trained on the log-transformed prices to better handle the skewed price distribution. The model aims to accurately predict listing prices while handling data noise and outliers.

## Results

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics evaluate the model's accuracy in predicting prices.
