# Intraday_Garch
This project implements a quantitative trading strategy that uses GARCH (Generalized Autoregressive Conditional Heteroskedasticity) models to predict volatility and generate intraday trading signals. The strategy combines daily volatility forecasts with intraday technical indicators to identify trading opportunities.

## Key Features
GARCH(1,3) model for volatility forecasting

Daily volatility prediction premium calculation

Intraday technical indicators (RSI, Bollinger Bands)

Combined daily and intraday signals for trade execution

## Requirements
Python 3.x
pandas
numpy
matplotlib
arch (for GARCH models)
pandas_ta (for technical indicators)
tqdm (for progress bars)
 ## Data Sources
Simulated daily price data (CSV format)

Simulated 5-minute intraday price data (CSV format)
