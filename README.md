# Gold ID Forex Software

This code represents the implementation of the Gold ID Forex Software, developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/gold-id-forex-software-review-protecting-account-equity-with-automated-cutloss/).

## Trade Functions

### noMartingale(double lotSize)
This function implements the no martingale trading strategy. It takes the lot size as a parameter and executes the code logic accordingly. 

### gridSupport(double lotSize)
This function incorporates the grid support feature. It takes the lot size as a parameter and executes the code logic accordingly.

### automaticCutLoss(double equity)
This function incorporates the automatic cutloss system. It takes the equity value as a parameter and executes the code logic accordingly.

## Performance Optimization

### optimizePerformance(double deposit)
This function optimizes the software for best performance with a minimum deposit of $1000. If the deposit is less than $1000, it prints a message and returns -1. Otherwise, it executes the code logic to optimize the performance.

## Compatibility

### verifyCompatibility(string symbol, string[] accountTypes, int leverage)
This function verifies the compatibility of the software with the trading symbol, account types, and leverage. It checks if the symbol is 'XAUUSD' (GOLD) and if the leverage is 1:500. If any of these conditions fail, it prints a message and returns -1. Otherwise, it tests and verifies compatibility with different account types using the code logic.

## Testing and Reliability

### testSoftware(int startYear, int endYear)
This function thoroughly tests the software using real ticks from the specified start and end years. It checks if the testing period is at least 4 years. If not, it prints a message and returns -1. Otherwise, it executes the code logic to test the software.

## Main function

### OnInit()
The main function initializes the software. It sets the lot size, equity, start year, and end year variables. 

Then, it verifies the compatibility of the software using the verifyCompatibility() function. If the compatibility check fails, it returns -1.

Next, it optimizes the performance of the software using the optimizePerformance() function. If the performance optimization fails, it returns -1.

After that, it tests the software using the testSoftware() function. If the testing fails, it returns -1.

Finally, it executes the trade functions (noMartingale(), gridSupport(), and automaticCutLoss()) and returns the INIT_SUCCEEDED constant if all the trade functions execute successfully.

Please note that ForexRobotEasy is not the official developer of this product. This code is only a sample that can work as described in the mentioned product. To find the official developer of this product, please use MQL5.
