# Economic Indicators and Google Trends Analysis

This repository contains a Jupyter notebook that analyzes the relationship between Google search trends and various economic indicators, such as Tesla stock price, Bitcoin price, and unemployment rates in the U.S. Using data from Google Trends, Yahoo Finance, and FRED (Federal Reserve Economic Data), the analysis attempts to uncover correlations and patterns that might reveal connections between online interest and economic outcomes.

## Project Overview

Google Trends gives us an estimate of search volume for specific topics, which can reflect public interest or concern. This project investigates:

1. **Tesla Stock Price vs Search Trends** - Analyzing if Google search popularity for Tesla correlates with changes in the stock price.
2. **Bitcoin Price vs Search Trends** - Studying the relationship between Bitcoin-related searches and its monthly price changes.
3. **Unemployment Benefits Search vs Unemployment Rate** - Exploring the link between searches for unemployment benefits and the actual unemployment rate.

## Data Sources
The data for this analysis comes from the following sources:
- [Unemployment Rate from FRED](https://fred.stlouisfed.org/series/UNRATE)
- [Google Trends](https://trends.google.com/trends/explore)
- [Yahoo Finance for Tesla Stock Price](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)
- [Yahoo Finance for Bitcoin Stock Price](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

## Notebook Contents

The Jupyter notebook includes:
1. **Data Exploration**: Importing the data and exploring key metrics such as trends, minimum/maximum values, and periodicity of the time series.
2. **Data Cleaning**: Handling missing values, converting dates, and resampling daily Bitcoin data to monthly data.
3. **Data Visualization**: Visualizing the trends between search popularity and financial metrics using line charts and customized plots.
4. **Analysis of Trends**: Understanding if spikes in search interest correlate with changes in stock prices or unemployment rates.

## Dependencies

- Python 3
- Pandas
- Matplotlib

You can install the required dependencies using:

```bash
pip install pandas matplotlib
```

## Usage

1. Clone the repository:

```bash

git clone https://github.com/yourusername/economic-trends-analysis.git
```

2. Navigate to the repository directory:

```bash
cd economic-trends-analysis
```

3. Open the Jupyter notebook:

```bash
jupyter notebook Economic_Indicators_Analysis.ipynb
```

## Insights and Observations

- Tesla: The relationship between Tesla search volume and stock price changes may indicate a correlation during significant price shifts.
- Bitcoin: Major spikes in Bitcoin-related searches appear to align with large price movements, which suggests that public interest might track volatility.
- Unemployment: The search interest in unemployment benefits tends to increase during periods of rising unemployment, especially during economic downturns.

## License

This project is licensed under the MIT License.
