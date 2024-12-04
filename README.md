# Algo_trading
Tried to simplify the option segment with Python 
                                                             Strategies
Components: (For volatile markets)
ATM IV
Spread
Steps:
Check the sensibull data of ATM IV.
Go ahead if the IV is above 15, don't do anything if it is below 15.
Check the spread (Price of call option + Price of put option) of Nifty weakly strikes (in the money and at the money strike).
If the difference of spreads between strikes of at the money and in the money is getting smaller and smaller then that is a green signal (i.e. market has volatility). For example, it gets 10 from 15.
The decision of buying a call or put option is based on the sensibull chart, if the ATM IV line is above the candle stick of closing price of nifty on spot then go for buying the call option otherwise buy a put option.
