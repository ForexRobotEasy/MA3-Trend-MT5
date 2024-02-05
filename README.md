# MA3 Trend MT5 ReadMe File

This code is an indicator called MA3 Trend for MetaTrader 5. It calculates and displays three moving averages (MA) on the chart. The indicator uses three input parameters: maPeriod1, maPeriod2, and maPeriod3, which represent the periods for the first, second, and third moving averages, respectively. The indicator also allows customization of the MA line color and width.

## Indicator Settings

- `maPeriod1`: Period for the first MA (default: 10)
- `maPeriod2`: Period for the second MA (default: 20)
- `maPeriod3`: Period for the third MA (default: 30)
- `maColor`: Color for the MA lines (default: Green)
- `maWidth`: Width for the MA lines (default: 2)

## Indicator Buffers

- `maBuffer1[]`: Buffer for the first MA values
- `maBuffer2[]`: Buffer for the second MA values

## Initialization Function (OnInit)

- Maps the indicator buffers to the corresponding buffers
- Sets the indicator line style, label, draw begin, and shift for both MA lines
- Sets the indicator colors

## Iteration Function (OnCalculate)

- Checks if there are enough bars to calculate MA values
- Calculates the MA values using the iMA() function
- Sets the MA values in the indicator buffers
- Returns the number of calculated bars

Please note that this code is a sample and not the official code developed by Forex Robot Easy Team. The official developer of this product can be found using MQL5.

For detailed reviews and trading results of this product, please visit the [MA3 Trend MT5 Review](https://forexroboteasy.com/forex-robot-review/ma3-trend-mt5-review-high-accuracy-forex-indicator/) on Forex Robot Easy website.

Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in the product.
