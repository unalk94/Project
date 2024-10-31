# Crypto Trading Dashboard With Indicator Signals
This dashboard is a Dash application designed to visualize real-time cryptocurrency data and generate trading signals based on popular technical indicators.

## Features
Fetches real-time cryptocurrency data from Binance.

Displays interactive candlestick charts for various time frames (from 1 minute to 1 day).

Calculates and displays trading signals based on technical indicators like RSI, MACD, Bollinger Bands, PSAR, and CCI.

Clear display of buy and sell signals.

Live data table showing current price, indicator values, and signals.

## Technologies Used
Python: Programming language.

Dash: Web application framework.

Plotly: For creating interactive charts.

Binance API: To fetch cryptocurrency data.

TA-Lib: To calculate technical indicators.

# Installation
## Install required Python packages:

``` 
pip install pandas
pip install numpy
pip install backtrader
pip install dash
pip install plotly
pip install binance.client
pip install ta
pip install ta.momentum
pip install ta.volatility
pip install dash
pip install datetime
 ```

Set up your Binance API keys and secret keys.

Usage
Open the dashboard in your web browser (default is http://127.0.0.1:8050/).

Select the cryptocurrency and time frame you want to monitor.

Analyze the candlestick chart and trading signals.

View the latest information in the live data table.

The application currently supports only the Binance exchange.

### !! Trading signals are for udecational purposes only and should not be considered financial advice !!

There may be delays in real-time data.

Contributing
Contributions and improvements are welcome! Please submit an issue or a pull request.

License
This project is licensed under the MIT License.
