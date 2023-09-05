# stock analysis stock

## Project 1: Analysis of crossing EM 20 with relationship of trend and trading volume

**Data:**
- Retrive price data from yfinance api.
- Stocks composition
Sector
Commercial Services       22
Communications             3
Consumer Durables         14
Consumer Non-Durables     13
Consumer Services         20
Distribution Services      7
Electronic Technology     32
Energy Minerals           10
Finance                   87
Health Services            9
Health Technology         92
Industrial Services       12
Miscellaneous              3
Non-Energy Minerals        9
Process Industries        16
Producer Manufacturing    27
Retail Trade              16
Technology Services       51
Transportation            12
Utilities                 10

**Objective:** 
The aim of this project is to analyze how stocks react when they cross downwards through the moving average of 20 days. We are particularly interested in the relationship between this trend and trading volume.

### Assumptions:
- Day to breakeven is calculated based on how long it takes for the stock to recover to its previous close.
- Maximum Drawdown: This metric is determined by finding the lowest price point during the period before the stock recovers to its breakeven point. This is then compared to the closing price on the day the stock crossed the 20-day moving average.
- Tread: EMA20 above the EMA200 is defined as uptrend
- Trading volume: Trading volumn graeter than MA20 of that is defined as high trading volumn

## Conclusion:
- There is a high probability that when a stock closes below its 20-day moving average, it will eventually recover. However, the risk of not reaching the breakeven point is significant. Graphs depicting the relationship between the days taken to breakeven and the maximum drawdown suggest that if the drawdown exceeds 20%, there's a higher chance it will take a prolonged period to recover, or it might never reach the breakeven point at all.

