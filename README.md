# Time-Series-Analysis

[![](https://img.shields.io/badge/Python-blue?style=for-the-badge)](https://github.com/hamzamohdzubair/redant)
[![](https://img.shields.io/badge/Library-Statsmodels-yellow?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Model-ARIMA-blueviolet?style=for-the-badge)](https://hamzamohdzubair.github.io/redant/)
[![](https://img.shields.io/badge/Library-Matplotlib-orange?style=for-the-badge)](https://crates.io/crates/redant)

![](https://img.shields.io/static/v1?label=&message=PlotAcf&color=green)
![](https://img.shields.io/static/v1?label=&message=PlotPAcf&color=yellow)
![](https://img.shields.io/static/v1?label=&message=GridSpec&color=blue)

## Research Question
Can we analyze trends and forecast daily revenues for the six months using time series models?

## The Goal of the data analysis
The goal of this data analysis is to find out if Teleco's past revenues have a trend that can be analyzed and whether these trends can be used to forecast future revenues using time series models.


![image](https://github.com/secil-carver/Time-Series-Analysis/assets/77639654/d03a62d4-49f4-42ee-a66e-9ac22945dad7)

## Assumptions of a time series model
Time series models assumptions are:
- **Time series is stationary** - Stationary data has a flat mean without trend, constant variance, and constant autocorrelation structure over time with no periodic fluctuations. To make a non-stationary series stationary we can differentiate the data, take the logarithm of the data, or take the square root of the data.

![image](https://github.com/secil-carver/Time-Series-Analysis/assets/77639654/d6df7ae4-3990-47ce-ba89-64179826fbc1)

- **Time series does not have autocorrelation** - Autocorrelation or serial correlation is the correlation of a time series with a lagged version of itself. If there are any correlations present, they indicate that past values influence current ones. Autocorrelation is useful in technical analysis because past trends are helpful in generating forecasts. However, they are not good for statistical tests because these tests require independent observations.

![image](https://github.com/secil-carver/Time-Series-Analysis/assets/77639654/48738a36-878b-43ba-94db-287853c2cbc3)
