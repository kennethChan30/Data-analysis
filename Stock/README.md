# Stocks analysis

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

### Over Picture

- **Recovery Rate**: Overall stocks have over an 85% chance to return to their previous levels.
- **Recovery Time**: Typically, stocks take 20 days to recover. However, the maximum drawdown can be as high as 90%.
- **Further Losses**: For stocks that do not recover, 50% of them will continue accumulating further losses, averaging around 40%.

### Consideration of Trend

- **Uptrend Recovery**: While there's a slightly higher recovery rate during an uptrend, it doesn't significantly affect the days to breakeven or the maximum drawdown.
- **Unrecovered Cases in Downtrend**: Stocks in a downtrend tend to incur more losses when they don't recover.

### Consideration of Trading Volume

- **Recovery Rate**: A slightly higher recovery rate is observed with lower trading volume.
- **Days to Breakeven**: Stocks with lower trading volume have a lower day to breakeven.
- **Unrecovered Cases**: Despite the aforementioned benefits, lower trading volume leads to more significant losses when stocks fail to recover.

### Day to Breakeven vs Maximum drawdown

- **Relationship**: No significant correlation between days to breakeven and maximum drawdown.
- **Drawdown > 20%**: Stocks with a maximum drawdown greater than 20% often require more time to recover or might not recover at all.

