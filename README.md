# OnBoard Stats MT5

[![Forex Robot Easy](https://forexroboteasy.com/wp-content/uploads/2019/04/forex-robot-easy-logo.png)](https://forexroboteasy.com/forex-robot-review/onboard-stats-mt5-review-streamline-forex-trading-insights/)

## Description
OnBoard Stats MT5 is a trading indicator that provides essential information and statistics about the symbols and their orders. This code represents a sub-panel of the indicator called 'Symbols Order Statistics'. It is developed by the Forex Robot Easy Team and can be found on their website at [forexroboteasy.com](https://forexroboteasy.com).

The Symbols Order Statistics sub-panel retrieves order statistics for a specific symbol. It determines the order type (market or pending), symbol name, and order status. It also allows for color-coding of symbol rows with pending orders and changing the chart to a specific symbol when clicking on a symbol row.

Please note that ForexRobotEasy is not the official developer of this product. This code serves as a sample implementation and can work as described in the OnBoard Stats MT5 product. To find the official developer of this product, please refer to the MQL5 marketplace.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/onboard-stats-mt5-review-streamline-forex-trading-insights/).

## Usage
To use the Symbols Order Statistics sub-panel, follow these steps:

1. Call the `SymbolsOrderStatistics()` function.
2. The function retrieves the order type, symbol name, and order status using the corresponding helper functions `GetOrderType()`, `GetSymbolName()`, and `GetOrderStatus()`.
3. If the order type is 'pending', the `ColorCodeSymbolRow()` function is called to color-code the symbol row.
4. The `ChangeChartBySymbolRow()` function allows for changing the chart to a specific symbol when clicking on a symbol row.

## Helper Functions
### GetOrderType()
This function retrieves the order type (market or pending). The code to retrieve the order type is not provided in this sample code.

### GetSymbolName()
This function retrieves the symbol name. The code to retrieve the symbol name is not provided in this sample code.

### GetOrderStatus()
This function retrieves the order status. The code to retrieve the order status is not provided in this sample code.

### ColorCodeSymbolRow(string symbol)
This function color-codes the symbol row. It uses different colors for different symbols with pending orders. The code to color-code the symbol row is not provided in this sample code.

### ChangeChartBySymbolRow(string symbol)
This function changes the chart to a specific symbol when clicking on a symbol row. The code to change the chart is not provided in this sample code.

## License
This code is provided by Forex Robot Easy Team as a sample implementation for the OnBoard Stats MT5 indicator. For the official license and terms of use, please refer to the MQL5 marketplace or contact the official developer.
