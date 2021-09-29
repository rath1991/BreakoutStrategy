# BreakoutStrategy
* Uses simple breakout rules and generated long and short signals based on comparison between low, high and close prices. 
* However, such a rule leads to enormous amount of signals resulting in high signal to noise ratio. 
* These signals are passed through a filter and then signal returns are calculated . 
* Looks for outliers and removes them using Kolmogorov Smirnov (KS) test. 
