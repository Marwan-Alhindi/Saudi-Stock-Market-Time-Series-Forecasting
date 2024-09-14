# Saudi Arabia Exchange Prediction using Time Series Analysis Techniques

## Languages and Tools

- **R**: Used for time series data analysis and modeling.
- **TSA** and **rugarch**: For ARIMA and GARCH model fitting and diagnostics.
- **ggplot2** and **corrplot**: For data visualization.

## Overview

This project applies advanced time series analysis techniques to forecast the closing values of four significant stock markets in Saudi Arabia, namely Al Rajhi, SNB, Alinma, and Sabic. Using both ARIMA and GARCH models, the analysis predicts market values for a ten-month period based on historical data. The findings provide valuable insights into the behavior and potential future trends of these markets, offering a powerful tool for strategic decision-making.

### Key Learnings

1. **Time Series Data Cleaning and Preparation**:
   - Mastered techniques to clean and filter data, handling missing values and converting time series data into a format suitable for modeling.
   - Used end-of-month data for each stock to focus on long-term trends rather than daily fluctuations.

2. **Data Visualization & Descriptive Statistics**:
   - Performed comprehensive data visualization and statistical analysis to understand the distribution, variance, and normality of stock price data.
   - Gained insights into market dynamics through box plots, mean value comparisons, and normality tests (Shapiro-Wilk test).

3. **Stationarity and Differencing**:
   - Applied the Augmented Dickey-Fuller (ADF) test to ensure that the time series is stationary, a key requirement for ARIMA modeling.
   - Differencing techniques were used to remove trends and achieve stationarity for better model performance.

4. **ARIMA and GARCH Model Fitting**:
   - Built ARIMA models to capture autocorrelation and predict future values based on past observations.
   - Enhanced the models by incorporating GARCH to account for the changing volatility observed in the markets, particularly in Sabic and Al Rajhi.

5. **Model Evaluation and Diagnostics**:
   - Used AIC, BIC, and residual analysis to evaluate model performance and select the best models for each market.
   - Performed diagnostic checks to ensure that the residuals were appropriately modeled and that the chosen models fit the data.

### Applications and Future Use

The skills gained in this project will allow me to:
- **Stock Market Forecasting**: Apply ARIMA and GARCH models to forecast future stock prices and assist in financial decision-making.
- **Risk Management**: Understand market volatility and develop models that account for fluctuating variances, allowing for more accurate risk predictions.
- **Time Series Forecasting in Other Domains**: Use these techniques to forecast data in fields like sales, demand forecasting, and environmental data analysis.

### How to Use

1. **Requirements**:
   - R programming language
   - Packages: `ggplot2`, `dplyr`, `TSA`, `forecast`, `tseries`, `rugarch`, among others listed in the `Libraries` section of the report.

2. **Running the Analysis**:
   - Clone this repository.
   - Install the necessary packages listed above.
   - Run the R scripts to perform the time series analysis and forecasting.
   - The project includes data for four Saudi Arabian markets and can be adapted to other datasets for similar analysis.
