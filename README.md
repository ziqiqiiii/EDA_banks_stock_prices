# Exploratory Data Analysis (EDA) for banks' stock prices

In this data project, I will focus on exploratory data analysis of stock prices. this project is just meant to practice my visualization and pandas skills, it is not meant to be a robust financial analysis or be taken as financial advice.

- [Banks list](#Banks list)
- [Data](#Data)
  
#### Banks list
- Bank of America (BAC)
- CitiGroup (C)
- Goldman Sachs (GS)
- JPMorgan Chase (JPM)
- Morgan Stanley (MS)
- Wells Fargo (WFC)

#### Data
I got the data from Yahoo Finance
```python
import yfinance as yf
.
.
tickers = ['BAC', 'C', 'GS', 'JPM', 'MS', 'WFC']
DF = yf.download(tickers, start, end)
DF.head()
```
