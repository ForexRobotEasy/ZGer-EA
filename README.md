# ZGer EA ReadMe File

This ReadMe file provides information about the ZGer EA code.

## Description
The ZGer EA is an expert advisor that analyzes candle bar behavior and generates buy and sell signals based on specific trading criteria. It is designed to be used in forex trading.

## Developer Information
- Official Developer: Not provided
- Sample Code: ForexRobotEasy Team
- Product Review and Trading Results: [ZGer EA Review - Unveiling the Power of Gold Auto Trade Strategy](https://forexroboteasy.com/forex-robot-review/zger-ea-review-unveiling-the-power-of-gold-auto-trade-strategy/)

## Required Input Parameters
1. MinimumDeposit: Minimum deposit required for the EA to function properly. Default value: 800.
2. MaxTradeSize: Maximum trade size allowed for the EA. Default value: 35.

## Expert Functions
### Initialization Function - `OnInit()`
- Checks if the minimum deposit requirement is met.
- Returns INIT_SUCCEEDED if the requirement is met.
- Returns INIT_FAILED if the requirement is not met.

### Tick Function - `OnTick()`
- Analyzes candle bar behavior and generates buy and sell signals based on the current and previous price levels.
- If the current close price is higher than the previous high, a sell signal is generated.
- If the current close price is lower than the previous low, a buy signal is generated.

### Deinitialization Function - `OnDeinit(const int reason)`
- Performs any necessary cleanup tasks.

### Custom Trading Functions
1. `Buy()`: Places a buy order based on specific trading criteria.
2. `Sell()`: Places a sell order based on specific trading criteria.

## Disclaimer
ForexRobotEasy is not the official developer of the ZGer EA. This code is provided as a sample and may not fully represent the actual product. To find the official developer of this product and for detailed reviews and trading results, please visit the [ZGer EA Review - Unveiling the Power of Gold Auto Trade Strategy](https://forexroboteasy.com/forex-robot-review/zger-ea-review-unveiling-the-power-of-gold-auto-trade-strategy/) page.

## Additional Resources
- For more information about the MQL5 programming language and to find the official developer of the ZGer EA, please visit [MQL5](https://www.mql5.com/).
