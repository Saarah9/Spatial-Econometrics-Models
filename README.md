# Spatial-Econometrics-Models
## Overview
This project implements key spatial econometric models using Python:
- **OLS (Ordinary Least Squares)**: A traditional linear regression model.
- **Spatial Lag (FAR)**: Captures spatial dependence by including a spatially lagged dependent variable.
- **Spatial Error (SEM)**: Accounts for spatial autocorrelation in the error terms.

Additionally, spatial diagnostics such as Moran's I are performed on OLS residuals to detect spatial dependence.

## Features
- **Spatial Weight Matrix**: Automatically generated for a 25x20 grid (500 observations).
- **Model Summaries**: Output from OLS, Spatial Lag, and SEM models.
- **Spatial Diagnostics**: Moran's I statistic for OLS residuals.
## Dependencies
The required Python libraries are:
- numpy
- pandas
- spreg
- libpysal
- scipy
- esda
