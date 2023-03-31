# bollinger-measurement


//This is a code for a custom technical analysis indicator in TradingView. Specifically, it is a Bollinger Band Length Measurer that calculates the length of the Bollinger Bands and the percentage change in the length of the bands over time.

Bollinger Bands are a type of technical analysis indicator that measures the volatility of an asset's price. They consist of an upper band, a lower band, and a middle band, which is typically a moving average. The upper and lower bands are typically set two standard deviations away from the middle band.

In this code, the length of the Bollinger Bands is calculated using the "length" and "mult" inputs, which determine the number of periods used in the calculation and the number of standard deviations from the middle band, respectively.

The "bandLength" variable is then calculated by subtracting the lower band from the upper band. The "lengthDiff" variable is then calculated by taking the percentage change in the length of the bands over time, which is determined by subtracting the current band length from the previous band length and dividing by the previous band length.

Finally, the "oscillator" variable is plotted, which is a number that ranges from 1 to 100 and represents the percentage above or below the 50 midpoint of the Bollinger Band Length Oscillator. A value above 50 indicates that the length of the bands is increasing, while a value below 50 indicates that the length of the bands is decreasing. The 50 midpoint is represented by the "Middle Line" horizontal line.
