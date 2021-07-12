# Equity-Derivative

The goal of this project is to retrieve and vizualize historical implied and realized volatilities in a select group of retail traded equities.

Once the data has be retrieved, it will be analyzed using a combination of Principal Component Analysis and Boosted Random Forests (SMOTEEN) to classify certain dates as potential position entry/exit points.

The end goal will be to generate an algorithm, trained and tested on historical data, that can provide a prediction on when a straddle position should be entered vs a covered call position on volatility divergence. Results will be compared against those in the paper/strategy provided by Barclay's. [U.S. Equity Derivatives Strategy - Impact of Retail Options Trading](https://www.docdroid.net/5gM68EW/barclays-us-equity-derivatives-strategy-impact-of-retail-options-trading-pdf#page=2)
