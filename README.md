# Forecasting number of visitors

`statlearning.py`: statistical + visualization codes

`forecast.py`: forecasting models + visualization codes

_put them in the same folder with jupyter notebook file while running it_

## Dataset:
Year: 1991 - 2016
Variable: 'Date', 'Number of Visitors'
Size: 312 observations

## [EDA - Number of Visitors](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/reports/EDA%20_%20Predictor%20Selection.pdf)
- systematically long-term increasing trend
- clear pattern of seasonality, seasonal variation is proportional to the trend
- a severe decline in 2003
- no evidence of cyclic behavior
![EDA](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/image/EDA1.png)

### Autocorrelation
The autocorrelation plot of the number of visitors shows that the autocorrelation becomes smaller as the lags increase due to the trend
![Autocorrelation](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/image/EDA-Autocorrelation.png)

### Decomposition
- upward trend
- seasonal pattern
- irregular fluctuations and noises that represent outliers and missing values.
![Decom1](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/image/EDA-Decomposition1.png)
![Decom2](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/image/EDA-Decomposition2.png)

## [Models](https://github.com/shaw6741/Time-Seriesl-Analysis/blob/master/reports/Modelling%20_%20Results.pdf)
- Seasonal Random Walk 
- Additive Holt-winters Smoothing (AHW)
- Multiplicative Holt-winters smoothing (MHW)
- AHW + Log transformation



