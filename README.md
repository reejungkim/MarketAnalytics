# Reporting Automation


This repositoyr is divided into two parts

### 1. Portfolio weight optimization based on Markowitz portfolio theory
[See Jupyter Notebook](S%26P%20100%20Analytics%20-%20Markowitz%20portfolio.ipynb)

Objective 1: Automate process of checking historical stock prices and return list of highest average returns with lowest volatility.

Objective 3: Web scraping news articles related to the stock when there was highest volatility.

Objective 2: Get optimal weight of portfolio based on [Modern portfolio theory](https://en.wikipedia.org/wiki/Modern_portfolio_theory)


#### Application deployed to Heroku: 
[Check Application](https://optimizingportfolio.herokuapp.com/)


### 2. Market analytics ETL
[See Jupyter Notebook](S%26P%20100%20Analytics.ipynb)
  - Loads stock data of S&P 100 companies ranged from today to given periods of days
  - Picks five most volatiled tickers and five best performed tickers
  - Scrapes searched news of companies on the dates where highest volatility occured
  

