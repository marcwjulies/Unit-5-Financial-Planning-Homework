# Unit-5-API-Homework Financial Planning
The homework has three requirements
- Personal Financial Planner
- Retirement Planning Tool
- Early Retirement Analysis

## Personal Financial Planner

The analysis uses the [Alternative Crypto API](https://alternative.me/crypto/api/) to read the Cryptocurrency ticker prices and also [ALPACA API](https://alpaca.markets/) to read the stocks prices using `requests` library in the Python.

Based on amount of the crypto tokens and the stocks held by the Credit Union members, their total personal savings are calculated using the prices retrieved through the above listed API data.

This is then compared to their ideal emergency fund amount (roughly 3 times their monthly income) and an analysis is performed whether the members have enough savings for the emergency.

## Retirement Planning Tool

The analysis uses the [ALPACA API](https://alpaca.markets/) to read the historical stocks prices for last 7 years using `requests` library in the Python.

The data is then used to perform Monte Carlo Simulations using the `MCForecastTools` toolkit which can be found [here](Resources/MCForecastTools.py).

The simulation is then used to predict the future value of $20,000 initial investments with 95% confidence levels.

## Early Retirement Analysis

This is the optional challenge that is performed to re-run the retirement analysis with higher ratio of stocks to bonds to predict the future investment value at 5 years and 10 years.



