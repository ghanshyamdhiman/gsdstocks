# gsdstocks
https://towardsdatascience.com/making-a-stock-screener-with-python-4f591b198261
Before I get into the code, I want to touch upon the stock screening criteria.
The current price of the security must be greater than the 150 and 200-day simple moving averages.
The 150-day simple moving average must be greater than the 200-day simple moving average.
The 200-day simple moving average must be trending up for at least 1 month.
The 50-day simple moving average must be greater than the 150 simple moving average and the 200 simple moving average.
The current price must be greater than the 50-day simple moving average.
The current price must be at least 30% above the 52 week low.
The current price must be within 25% of the 52 week high.
The IBD RS-Rating must be greater than 70 (the higher, the better). 
The RS rating is a metric of a stock’s price performance over the last year compared to all other stocks and the overall market.
