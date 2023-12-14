# Di Napoli Thrust Scanner Dashboard MT5

This code is a customizable scanner function that scans for the Di Napoli thrust pattern on multiple timeframes and symbols. It also includes a dashboard interface to display the scan results.

## Customizable Parameters
- `thresholdBars`: Specifies the number of bars required for the thrust pattern. Default value is 5.
- `symbolCopyCount`: Specifies the number of symbols to scan. Default value is 5.
- `customSymbols`: Specifies the custom symbols to scan. Default symbols are EURUSD, GBPUSD, and USDJPY.

## Scanner Function
The `ScanThrustPattern()` function scans for the Di Napoli thrust pattern on multiple timeframes. It loops through the specified timeframes and symbols, performs necessary calculations and conditions to determine the presence of the thrust pattern, and increments the thrust count if detected. The scan results are then displayed on the dashboard.

## Dashboard Interface
The `DisplayDashboard()` function is responsible for creating and displaying the dashboard interface. It uses the scan results to populate the dashboard.

## Initialization
The `OnStart()` function is the entry point of the program. It calls the `ScanThrustPattern()` function to perform the scanning and then calls the `DisplayDashboard()` function to display the results on the dashboard.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample and may not have the same functionalities as the official product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the official developer's website: [Di Napoli Thrust Scanner MT5 Review](https://forexroboteasy.com/forex-robot-review/di-napoli-thrust-scanner-mt5-review-optimized-forex-trading-tool/)
