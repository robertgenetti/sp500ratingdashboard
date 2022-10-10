# sp500ratingdashboard
I began this project with the aim to at the very least firmilirize myself with commonly used financial metrics for the purpose of price valuation and ranking along a buy sell scale. This project was fun to do and it gave me yet another example to add to my portfolio.

## Topic
Illustrate key performance metrics of finacial information into a collection of dashboards. The S&P 500, one of the most highly regarded group of companies provided a data set range from which to start my data analysis. The result was a convenient and easy to use dashboard to screen and display many of the financial metrics used for investing purposes. As an addintion I included a linear regression to display up-to-date buy or sell recommendations.

## Roadmap

1. Extract, Transform, and Load
    - Pull list of companies in S&P 500
    - Pull financial data from Yahoo Finance
    - Sort and transform data in Pandas
    - import dataframes into SQL Postgres Database
2. Analyze buy/sell ecommendation data in Python
    - Select features best suited
    - Transform data to limit outliers
    - Import into SQL Postgres Database 
3. Build Linear Regression with Fixed Effects in R
    - Explore data
    - Perform linear regression on test data
    - Use fixed effects to seperate sector bias
4. Design Tableau dashboard
    - Screener to filter companies based on specific measures
    - Overview with buy/sell readout from linear model
    - Income statement KPIs
    - Balance sheet KPIs
    - Cashflow statement KPIs