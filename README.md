# API_Homework: Fake Credit Union 
FinTech: Unit 5 Homework


A tool to help credit union members enhance their financial health designed for Fake Credit Union: FDIC Insured.  This will allow members to assess their monthly personal finances, and forcast a retirement plan based on cryptocurrencies, stocks, and bonds. 

### Files

* [Personal Finance Planner starter code](Starter_Code/financial-planner.ipynb)

* [MCForecastTools toolkit](Starter_Code/MCForecastTools.py)

---

### API Keys Needed

* ALPACA KEY

* ALPACA SECRET KEY

### APIs Used

* Current price in US dollars of bitcoin ('BTC') and ethereum ('ETH')

* Current closing prices for "SPY" and "AGG"

## Part 1 - Personal Finance Planner

Part 1 focuses on the personal finance planner appication portion of this tool.  Each member has a savings portfolio with cryptocurrencies, stocks, and bonds.

**Adjustable Variables Used**: These can all be updated without creating an error in the code

Monthly Household Income

`monthly_household_income` : $12,000<br>
_average household income for each member_

Amount of Crypto per member

`my_btc` : 1.2<br>
`my_eth` : 5.3

Amount of Shares per member

`my_agg` : 200<br>
`my_spy` : 50

## Part 2 - Retirement Planning

Part 2 focuses on using Monte Carlo simulations to project the portfolio performance at 30 years, 5 years, and 10 years using the same Adjustable Variables from Part 1.

**Adjustable Variables Used**: These can all be updated without creating error in the code

`years` = 30<br>
`initial_investment` = $20,000<br>
`investment_increase` = 1.5

`start_date` Comment in code to show where date can be updated to 5 years from today's date<br>
`end_date` Comment in code to show where date can be updated to today's date



