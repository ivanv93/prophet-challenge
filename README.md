# Prophet-Challenge

This project analyzes the relationship between Google search trends for MercadoLibre and its stock performance. Using data from January to June 2020, I explored patterns in search traffic and stock metrics, using time series forecasting with Prophet. I was provided assistance by some of my classmate, Nathan Bauer. Sean Morey, the instructor of the class, was a big help. I lastly received assistance from Luna Zhang, a BCS tutor. I also could not have been able to finish this code without the help from the BCS Xpert Learning Assistant.

## Data Sources

* Google Search Trends: Hourly data on search volume for MercadoLibre.

* Stock Prices: Daily closing prices of MercadoLibre stock.

## Analysis Overview

* Data Preprocessing:
   - Loaded and cleaned data from CSV files.
   - Merged search trends and stock price data into a combined DataFrame.

* Exploratory Data Analysis:
   - Visualized trends in search volume and stock prices.
   - Examined relationships between search traffic, stock volatility, and returns.

* Time Series Forecasting:
   - Utilized Facebook Prophet to forecast search trends.
   - Analyzed forecast components to identify trends by time of day and day of week.

## Key Findings

* Search Traffic Patterns:
  - Highest search volume throughout the week is typically on Tuesdays.
  - Peak hours occure in the late morning to early afternoon.
  - Lowest search traffic during a calendar year is in October.

* Correlation with Stock Metrics:
  - Moderate correlation between lagged search traffic and stock volatility.
  - Weak correlation between lagged search traffic and stock price returns.

* Near-term Forecast:
  - Positive trend in search popularity for MercadoLibre.

## Conclusion

The analysis provides insights into the impact of search trends on stock performance, highlighting potential opportunities for market prediction based on search behavior.
