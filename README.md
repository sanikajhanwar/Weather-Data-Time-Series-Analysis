# Weather Data Time Series Analysis

## Overview
This project analyzes weather data (temperature, humidity, wind speed, and pressure) using time series analysis techniques. It includes stationarity testing, random walk simulation, autocorrelation analysis, noise addition, and filtering to study data trends and forecasting potential.

## Features
- **Data Preprocessing:** Converts date format, checks for missing values, and selects relevant columns.
- **Stationarity Check:** Uses Augmented Dickey-Fuller (ADF) test to analyze trends.
- **Random Walk Simulation:** Compares actual temperature trends with a simulated random walk.
- **Wind Speed Analysis:** Uses Autocorrelation Function (ACF) and Durbin-Watson test to check dependencies.
- **Noise Addition & Filtering:** Adds Gaussian noise and applies a low-pass filter to remove noise.
- **Error Evaluation:** Computes Mean Squared Error (MSE) to measure filtering effectiveness.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Statsmodels
- SciPy
- Scikit-learn

## Usage
1. Load the dataset in Google Colab.
2. Run preprocessing steps to clean and prepare the data.
3. Perform stationarity tests and analyze time series properties.
4. Apply noise addition, filtering, and evaluate effectiveness using MSE.
5. Visualize results through graphs and statistical outputs.

## Results
- The temperature data is **non-stationary**, requiring transformation for forecasting.
- Wind speed shows **strong autocorrelation**, indicating dependency on past values.
- Low-pass filtering **effectively smooths** temperature trends but is **less effective for humidity** due to variability.

## Conclusion
This analysis provides insights into weather trends, data dependencies, and the impact of noise filtering. The results can assist in building predictive models for weather forecasting.

## Author
Sanika

## License
This project is open-source and available for modification and enhancement.
