# Features and Targets
Creating feature and target variables.

## Ideas
## Trend indicators
### Trending/Ranging indicator
- ADX: Average Directional Index https://www.incrediblecharts.com/indicators/adx-average_directional_index.php
  - ADX below 20 for any length of time indicates a ranging market;
  - ADX rising above 20 indicates the start of a new trend;

- Relative ADX and directional indicators https://medium.com/python-in-plain-english/creating-a-trading-strategy-based-on-the-adx-indicator-9a310ed4b258
- ATR: Average True Range Indicator https://www.incrediblecharts.com/indicators/average_true_range.php
  - High values warn of market tops and bottoms
  - Low values indicate ranging markets.

### Trend direction
- Linear regression slope
- Relative EMA: Exponential Moving Average
  - Go long when price crosses to above the moving average from below.
  - Go short when price crosses to below the moving average from above.
- It is said that the lookback of EMA should be half of the period we aim to track. https://www.incrediblecharts.com/indicators/moving_average.php

### MACD - Moving Average Convergence Divergence
- MACD Percentage, primarily used to trade trends
  - MACD Percentage = (12 Day EMA - 26 Day EMA) / 26 Day EMA
- Trade signal MACD
  - buy when MACD crosses above the signal line
  - sell when MACD crosses below the signal line
- Compare to MACD, MACD Percentage enables comparison between stocks at different prices.
https://www.incrediblecharts.com/indicators/macd-percentage-price-oscillator.php

### RSI Indicator - Relative Strength Index
- RSI
- Trade signal RSI
  - Ranging Markets
    - Set the Overbought level at 70 and Oversold at 30. Go long when RSI falls below the 30 level and rises back above it or on a bullish divergence where the first trough is below 30. Go short when RSI rises above the 70 level and falls back below it or on a bearish divergence where the first peak is above 70.
  - Trending Markets
    - Only take signals in the direction of the trend. Go long, in an up-trend, when RSI falls below 40 and rises back above it. Go short, in a down-trend, when RSI rises above 60 and falls back below it.

### Stochastic Oscillator
%K

### Volatility Range Indicator
https://medium.com/python-in-plain-english/the-volatility-range-indicator-creating-a-profitable-contrarian-trading-strategy-50609880ecf8
