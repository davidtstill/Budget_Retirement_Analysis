# Budget_Retirement_Analysis

The purpose of the analysis is to examine a customer's financial profile and help them plan for retirement. This was done by utilizing two different APIs - the Plaid API and the Alpaca API. 

The account_summary.ipynb file utilized the Plaid API to obtain the user's transaction data and income history. The Plaid API is a popular way for people to connect their financial data (i.e. bank transactions) to apps and services such as Venmo and Betterment. The information was stored in a DataFrame.   

The portfolio_planner.ipynb file utilized the Alpaca API, a service that let's write code to trade securities. I pulled historical data for a 60/40 portfolio using the SPY etf to represent the S&P 500 and the AGG etf to represent the performance of the U.S. bond market. I ran a Monte Carlo simulation to estimate the value of the portfolio over time. I also ran another simulation to estimate how much different withdrawal amount would impact one's ability to meet their income needs. 

