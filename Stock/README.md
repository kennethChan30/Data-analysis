# Stocks analysis

## Project 1: Analysis of crossing EMA 20 with relationship of trend and trading volume

**Data:**
- Retrive price data from yfinance api.

**Objective:** 
The aim of this project is to analyze how stocks react when they cross downwards through the moving average of 20 days.

### Assumptions:
- Day to Breakeven: The duration required to return to the closing price of the day preceding the crossover
- Maximum Drawdown: Represents the lowest price during the recovery period compared to the closing price on the day it crossed below the EMA20
- Carrying loss: The loss when the stocks hold do not recover on 31st July 2023, comparing closing price on the day to the closing price on 31st July 2023
- Trend: An EMA20 above the EMA200 is defined as an uptrend.
- Trading Volume: Trading volume greater than the MA20 is defined as high trading volume.
- The affect of dividends and stock-splits was neglected.


## Conclusion:

### Over Picture

- **Recovery Rate**: Overall stocks have over an 80% chance to return to their previous levels.
- **Recovery Time**: Typically, stocks take 20 days to recover. However, the maximum drawdown can be as high as 90%.
- **Further Losses**: For stocks that do not recover, 50% of them will accumulate more than around 40% further losses.

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

