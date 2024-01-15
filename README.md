# All in 1 Propsense MT5

This code is a sample implementation of the All in 1 Propsense MT5 forex trading robot. The robot is developed by the Forex Robot Easy Team and is designed to optimize forex trading with major USD currency pairs. It provides session visibility options and allows the user to define the number of historical fixes to display.

## Input Parameters

The code includes several input parameters that can be modified by the user:

- **numFixes** (default: 10): Number of historical fixes to display.
- **showSydneySession** (default: true): Show or hide the Sydney session.
- **showAsiaSession** (default: true): Show or hide the Asia session.
- **showLondonSession** (default: true): Show or hide the London session.
- **showNewYorkSession** (default: true): Show or hide the New York session.
- **currencyPairs**: An array of major USD currency pairs.
- **timeframe** (default: PERIOD_M5): The timeframe for trading.

## Initialization Function

The `OnInit()` function is called when the expert advisor is initialized. It prints the header information, sets the session visibility options based on the input parameters, and prints the session visibility information, currency pairs, timeframe, and number of historical fixes.

## Deinitialization Function

The `OnDeinit()` function is called when the expert advisor is deinitialized. It can be used to perform any necessary deinitialization tasks.

## Start Function

The `OnTick()` function is called on each tick of the price data. It is where the trading algorithm tasks are performed. In this sample code, it simply prints a message indicating the completion of the trading robot execution.

Please note that this code is a sample representation of the All in 1 Propsense MT5 forex trading robot. ForexRobotEasy is not the official developer of this product. The official developer can be found using MQL5. For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/all-in-1-propsense-mt5-review-optimize-forex-trading-with-major-usd-pairs/).
