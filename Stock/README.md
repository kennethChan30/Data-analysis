# stock analysis stock

## Project 1: Analysis of crossing EMA 20 with relationship of trend and trading volume

**Data:**
- Retrive price data from yfinance api.

**Objective:** 
The aim of this project is to analyze how stocks react when they cross downwards through the moving average of 20 days.

### Assumptions:
- Day to breakeven is calculated based on how long it takes for the stock to recover to its previous close.
- Maximum Drawdown: This metric is determined by finding the lowest price point during the period before the stock recovers to its breakeven point. This is then compared to the closing price on the day the stock crossed the 20-day moving average.
- Tread: EMA20 above the EMA200 is defined as uptrend
- Trading volume: Trading volume grater than MA20 of that is defined as high trading volume

## Conclusion:
- There is a high probability that when a stock closes below its 20-day moving average, it will eventually recover. However, the risk of not reaching the breakeven point is significant. Graphs depicting the relationship between the days taken to breakeven and the maximum drawdown suggest that if the drawdown exceeds 20%, there's a higher chance it will take a prolonged period to recover, or it might never reach the breakeven point at all.

