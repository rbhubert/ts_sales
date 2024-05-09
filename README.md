## Exploration, Analysis, and Forecasting of Superstore Sales Dataset

### Exploratory Analysis

We start with a exploratory analysis of the dataset, delineating columns, discerning data types, and investigating correlations among numeric variables.

### Sales Behavior Analysis by Category

Next, we look at how sales are doing for different types of products, both on a daily and monthly basis. This helps us understand if there are any trends or patterns.

### Time Series Decomposition

Utilizing both additive decomposition and STL (Seasonal-Trend Decomposition Procedure Based on Loess), we extract the following components:
- Trend: Reflects the long-term behavioral changes within the time series data.
- Seasonality: Captures the recurrent and predictable patterns recurring over similar time intervals.
- Noise/Residual: Represents the residual signals post-removal of trend and seasonality.

### Stationarity and Autocorrelation Analysis

We assess the stationarity of the time series data and proceed to examine its autocorrelation (ACF) and partial autocorrelation (PACF) using both computational methods and graphical visualization techniques.

### Forecasting

Our forecasting methodologies encompass:
- Auto Regression: Employing past values to predict current ones, we construct a linear regression model based on historical data.
- ARIMA Model: Leveraging lagged moving averages to smoothen the time series data and make informed predictions.

### Performance Metrics

To gauge the efficacy of our models, we utilize the following metrics with a 70/30 train-test split:
- Mean Squared Error (MSE): Measures the average squared differences between the predicted and actual values.
- Mean Absolute Error (MAE): Computes the average absolute differences between predicted and actual values.
- Root Mean Squared Error (RMSE): Represents the square root of the MSE, offering an interpretable measure of forecasting accuracy.
