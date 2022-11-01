# Quantitative-Momentum-Strategy

"Momentum investing" means investing in the stocks that have increased in price the most.

For this project, I built an investing strategy that selects the 50 stocks with the highest price momentum. Then calculate the recommended trades for an equal-weight portfolio of these 50 stocks.

I used the IEX Cloud API token as a data provider. A sandbox API token was used, which means that the data used is randomly-generated and has no cost associated with it.

The ouput is an excel sheet momentum_strategy.xlsx that lists all the stocks and the no of shares to buy for each of the stocks for the supplied portfolio value.
