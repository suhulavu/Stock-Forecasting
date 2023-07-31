
# Stock Forecasting

Time series analysis of Microsoft, Apple, Tesla, and Meta stocks
## Project Description
The purpose of this project is to model the closing price and volatility of the 4 stocks listed above. First, raw stock price data was downloaded using the yahoo finance python library. The Augmented Dickey-Fuller (ADF) test was utilized to determine the order of differencing required to make the data stationary. Next, PACF and ACF plots were used to determine possible values for the moving average and autoregressive components of the ARIMA model and AIC was used as the criterion to select the best set of parameters. After the model was trained, the residuals were analyzed using diagnostic plots as well as statistical tests such as the Ljung-Box test for autocorrelation and the Breusch-Pagan test for heteroskedasticity. If the results of these tests demonstrated that there was a change in variance over time, then GARCH was used to model the volatility of the returns.

### Methods Used
- Statistical Testing
- ARIMA Modeling
- GARCH Modeling
- Data Visualization

### Dependencies
- yfinance
- matplotlib
- statsmodels
- pandas
- scikit-learn
- arch
- tqdm

## Featured Results

View results on testing data and Tableau visualization at https://suhulavu.github.io/Stock-Forecasting/
## License

[MIT](https://choosealicense.com/licenses/mit/)

