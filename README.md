# Data-Science-Project-ENSO-Analysis

## Introduction 

> El Niño and the Southern Oscillation, also known as ENSO is a periodic fluctuation in sea surface temperature (El Niño) and the  air pressure of the overlying atmosphere (Southern Oscillation) across the equatorial Pacific Ocean. El Niño is so termed because it generally reaches full strength toward the end of the year, and early Christian inhabitants of western equatorial South America equated the warm water current and the resulting impacts with their holiday celebrating the birth of Jesus Christ (known as El Niño in Spanish)[^1] 

__Goal__:To analyse and explore of the [ENSO datasets](https://www.ncei.noaa.gov/access/monitoring/enso/soi) to create a predictive model for ENSO anomaly values. This project aims to use machine-learning techniques (train an xgboost regression model) to predict the values of the measurements of the Southern Oscillation Index (SOI) for the following few months. These indexes are strongly associated with _El niño_ phenomenon.
Given the nature of the datum, I decided to make time series forecasting using machine learning tools, namely the xgboost regression Python tool. So, we transform the time series forecasting into a regression problem. All the analysis is developed in this [Juypiter notebook file.](ENSO-data-analysis.ipynb)

## Outline 
    1. Data Pre-Processing
    2. Train-Test Splitting
    3. Calling the XGBoost Regressor
    4. Hyper Parameter Optimization
    5. Results and conclusion 
    6. Optional: Another approach to Hyper Parameter Optimization.

[^1]: [https://www.ncei.noaa.gov/access/monitoring/enso/](https://www.ncei.noaa.gov/access/monitoring/enso/)
