# Time-Series
### Linear Regression, ARMA, ARIMA and GARCH Models

Summary and Analysis:

Linear Regression:

Out of sample root mean square is less than the in sample root mean square, which is not ideal for any regression model./n Also, the error for in sample is greater than 0.5, that states that the residuals are fairly spread out from the best fit line. The RMSE for in out of sample is mopre acceptable as it is less than 0.5

ARMA, ARIMA and GARCH:

ARMA:

For a best fit model, p should be < 0.05. Above regression model has the p values for constant, auto-regressions, and moving average greater than the ideal value. So, the model is not a good fit.

ARIMA:

The ARIMA model used to forecast the yen futures price does not have the p value less than 0.05 for auto regression with any lag and for moving averages with any lag. So, it is not an ideal fit.

Comparing the AIC and BIC values for the models used to forecast,
The AIC and BIC values for Garch are the best, which indicates that the volatility forecast is more accurate compared to the price forecast models used.
Among the ARMA and ARIMA models, ARMA has lower AIC and BIC values and hence better fit than ARIMA.

Conclusions:

1. Based on the analysis, the volatility of the yen futures is increasing over the period of time, so, I would buy the security now, in order to gain from the volatility changes.

2. Risk of the yen futures security is going to increase.

3. The models used are not ideal fit for the input data. I am not confident to use these models for trading.

