# Analyzing-stock-performance
Data Extraction and Data Visualization

In this project, I will extract financial data like historical share price and quarterly revenue reportings from various sources using Python libraries and webscraping on popular stocks. After collecting this data I will visualize it in a dashboard to identify patterns or trends. The stocks I will analyse are **AMD, Netflix, GameStop, and Tesla.**

**Data Extraction**
The **stock ticker** is a report of the price of a certain stock, **updated continuously throughout the trading session by the various stock market exchanges**. I will be using the **y-finance API** to obtain the stock ticker and extract information about the stock, since it allows us to extract data for stocks returning data in a pandas dataframe.
Not all data is available via API, hence I will also be using **wescraping tools** to obtain financial data. We will extract historical stock data from a web-page using the **Beautiful Soup Library**.
