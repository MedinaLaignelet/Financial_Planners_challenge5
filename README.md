#Financial Planning Challenge#
Objective: To create a financial planning tool for emergencies and for retirement using Python code and APIs requests to evaluate the Market Value of a crypto and a stock/bond wallet and determines if an emergency fund can be founded.  As a second part to the challenge, Alpaca APIs will be used to obtain historical data from a Stock and Bond and Montecarlo simulations will be run to evaluate the potential outcomes at different retirement horizons.
Please note that when running the MCForecast tool the outcomes are correct but a repeated message shows when building the outcome dataframe.  The code with the Python Code is found in the Jupyter Lab file template titled “Financial Planner.”

##Create a Financial Planner for Emergencies##
After downloading the necessary files, I also prepared the .env file that will be used to obtain the Market Value of the Crypto and Stock/Bond wallets through alpaca requests.
First, the code imposts the necessary libraries to support the different steps to complete the challenge.  After determining the tickers for the crypto and stock/bond wallets, we use a request to obtain the market prices from the URLS provided and using API requests.  For the Crypto prices, once the JSON response is received, we then locate the index place of each Crypto and calculate the crypto and wallet market value.  For the Stock/Bind wallet, we evaluate the Alpaca response, create the closing process as variables, and calculate the stock/bond wallet market value.
###Evaluate Emergency Fund###
For this section the code will take the market values of the crypto and stock/bond wallets to combine them and determine if the total market value is enough to set up an emergency fund.  The code will print the response based on the Total Market Value of the wallets combined  and the $36,000 emergency fund requirement.
###Create a Financial Planner for Retirement##
The code uses an Alpaca API request to obtain historical values to evaluate the retirement portfolio.  The code then runs Monte Carlo Simulations using a provided MCForecast tool code to help with the retirement planning tool.  The MC simulations results are plotted and their cumulative returns and statistics calculated. The simulations run with different horizons to evaluate cumulative returns and summary statistics and use the metrics calculated to provide different potential outcomes using a 95% confidence level.

###Coding References###
Berkeley Fintech Bootcamp -Module 4 and 5 Activities

	

