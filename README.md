# -APIs-
The Consumer Division of a company has decided to offer budgeting and financial planning services to customers. They want to build a report for customers that links to their banking and investment accounts and automatically refreshes the data and charts on login.

## In this assignment, I've conducted the following manipulations:

- Budget Analysis with Plaid
- Retirement Planner
- Financial Report 

# Budget Analysis
__In this section, I used Plaid API to obtain transaction and account data for the budget analysis section of the report to complete the following_:

- Generate a Plaid access token to access the Developer Sandbox
- Use the Access token to fetch account transactions from the sandbox (fetched the last 90 days of transactions from the sandbox)
- Performed basic budget analysis on the sandbox transaction and generate the plots
- Useed the API to fetch income data from the sandbox and print the following: 
    - Last Year's Income Before Tax 
    - Current Monthly Income 
    - Projected Year's Income Before Tax

# Retirement Planner
__In this section, I've used the Alpaca API to fetch historical closing prices for a retirement portfolio and then run Monte Carlo simulations to project the portfolio performance at 30 years; and used the Monte Carlo data to answer questions about the portfolio__.

- Monte Carlo Simulation (Used the Alpaca API to fetch historical closing prices for a traditional 60/40 portfolio using the SPY and AGG tickers to represent the 60% stocks (SPY) and 40% bonds (AGG))
- Run a Monte Carlo Simulation of 500 runs and 30 years for the 60/40 portfolio and plot the results
- Select the ending cumulative returns from the Monte Carlo simulation and calculate the interval values for a 90% confidence interval
- Using the ending cumulative returns, plotted a histogram of the results and plotted the 90% confidence interval as vertical lines on the histogram

# Retirement Analysis
__Used the Monte Carlo simulation data to answer the following questions__:
- expected cumulative returns at 30 years for the 10th, 50th, and 90th percentiles
- expected return in dollars at the 10th, 50th, and 90th percentiles, given an initial investment of $20,000
- determined if retirement income is equivalent to current income (4% withdrawal rate meet or exceed that value at the 10th percentile)
- determined how 50% increase in the initial investment ($20000) amount would affect the 4% retirement withdrawal. 



