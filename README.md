# Trading Keys MT5

## Description

This code represents a sample implementation of the Trading Keys MT5 system. Trading Keys MT5 is an advanced forex risk calculator that helps traders manage their risk effectively. This code provides the basic functionality of the system, including risk calculation, setting profit/stop loss/entry levels using visual lines, and enabling/disabling trailing stop.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trading-keys-mt5-review-advanced-forex-risk-calculator/).

## Usage

To use the Trading Keys MT5 system, follow these steps:

1. Set the global variables according to your preferences:
   - `riskPercentage`: Risk percentage per trade (default: 2)
   - `trailingEnabled`: Toggle for profit protection and trailing (default: false)
   - `trailingDistance`: Trailing stop distance in pips (default: 20)

2. Implement your main trading logic in the `OnStart()` function.

3. Optionally, you can implement additional functions for testing the software, delivering the completed code, providing documentation and instructions, and handling tick updates and deinitialization.

4. Call the necessary functions within `OnStart()` to perform risk calculation, set profit/stop loss/entry levels, and enable/disable trailing stop.

5. Compile and run the code in your MetaTrader 5 terminal.

## Functionality

### CalculateRisk()

This function calculates the risk amount based on the account balance or equity. It retrieves the current account information and calculates the risk amount using the specified risk percentage.

### SetLevels()

This function implements the drag-and-drop functionality for visual lines. Traders can set profit/stop loss/entry levels based on the position of these lines. The implementation details are not provided in this code and should be added according to the trader's requirements.

### EnableTrailing()

This function enables the trailing stop functionality. Traders can protect their profits and automatically adjust their stop loss level as the market moves in their favor. The implementation details are not provided in this code and should be added according to the trader's requirements.

### DisableTrailing()

This function disables the trailing stop functionality.

### OnStart()

This is the main function where the trading logic should be implemented. It calculates the risk per trade, sets profit/stop loss/entry levels, and enables/disables trailing stop based on the defined global variables.

### TestSoftware()

This function is for testing the software. The implementation details are not provided in this code and should be added according to the trader's requirements.

### DeliverCode()

This function is for delivering the completed code. The implementation details are not provided in this code and should be added according to the trader's requirements.

### ProvideDocumentation()

This function is for providing documentation and instructions. The implementation details are not provided in this code and should be added according to the trader's requirements.

### OnTick()

This function is called on each tick update. The necessary functions should be called within this function.

### OnDeinit()

This function is called when the code is deinitialized. The necessary functions should be called within this function.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of Trading Keys MT5. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trading-keys-mt5-review-advanced-forex-risk-calculator/).
