# API-Assignment #

## In this homework lesson we pull information regarding a deposit account and then projected a retirment portfolios performance. ##
 - We will be using the plaid and alpacas APIs to pull relevant stock information as well as sandbox banking info for a customer

## Here we load relevant Libraries and define a function that will help clean up the json info we pull from the plaid API

[.](<a href="https://imgur.com/Ma5hUqV"><img src="https://i.imgur.com/Ma5hUqV.jpg" title="source: imgur.com" /></a>)

## Using getenv to pull keys from a 'hidden' folder housing the API keys we have through plaid

[.](<a href="https://imgur.com/Y7QVSs0"><img src="https://i.imgur.com/Y7QVSs0.jpg" title="source: imgur.com" /></a>)

## Here I use standardized code snippets from plaid to connect to the plaid sandbox and pull the relevent information in JSON format. ##

[.](<a href="https://imgur.com/Ei02eeW"><img src="https://i.imgur.com/Ei02eeW.jpg" title="source: imgur.com" /></a>)

## Pulling up 90 days of transactions from the plaid sandbox for customer X

[.](<a href="https://imgur.com/2MWtoTf"><img src="https://i.imgur.com/2MWtoTf.jpg" title="source: imgur.com" /></a>)

## Now we convert the json file to a format we are more familiar with, a pandas DataFrame ##

[.](<a href="https://imgur.com/4l6nWVJ"><img src="https://i.imgur.com/4l6nWVJ.jpg" title="source: imgur.com" /></a>)

## Here we are viewing the json in an easier to chew way and can see it is a dictionary, so we can pull bits of information out of it ## 

[.](<a href="https://imgur.com/YSt64HX"><img src="https://i.imgur.com/YSt64HX.jpg" title="source: imgur.com" /></a>)

## Lets take a look at where this customer is spending their money the most by category ##

[.](<a href="https://imgur.com/3BKGV7C"><img src="https://i.imgur.com/3BKGV7C.jpg" title="source: imgur.com" /></a>)


# Next we will be using the alpacas API to pull Stock data #

## First we setup our API keys, given I dont use alpacas and will be using a new account in later algo trading projects I hard coded keys here for ease ##
 -  Then we setup the call to the API with relevant ticker and date info to pull into a pandas DataFrame 
[,](<a href="https://imgur.com/fMzIKF0"><img src="https://i.imgur.com/fMzIKF0.jpg" title="source: imgur.com" /></a>)

## Now to run a Monte Carlo simulation on our two stock tickers and see what we come up with ##

[.](<a href="https://imgur.com/IfRPh6u"><img src="https://i.imgur.com/IfRPh6u.jpg" title="source: imgur.com" /></a>)

## Now we could visualize that and see what all was calculated ##

[.](<a href="https://imgur.com/TU0TQIQ"><img src="https://i.imgur.com/TU0TQIQ.jpg" title="source: imgur.com" /></a>)

## Given an initial investment of $20,000, what is the expected portfolio return in dollars at the 10th, 50th, and 90th percentiles? ##

[.](<a href="https://imgur.com/d9TjS6O"><img src="https://i.imgur.com/d9TjS6O.jpg" title="source: imgur.com" /></a>)

## How would a 50% increase in the initial investment amount affect the 4% retirement withdrawal? ##

[.](<a href="https://imgur.com/amKvAN1"><img src="https://i.imgur.com/amKvAN1.jpg" title="source: imgur.com" /></a>)


# In this assignment we utilized pandas again, talked to API's and did some very crude 'machine learning' with the monte carlo simulation #
