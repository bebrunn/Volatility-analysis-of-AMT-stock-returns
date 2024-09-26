# Financial Econometrics I: Volatility Analysis of American Tower Corp Stock Returns

## Project Overview

This project estimates and compares several econometric models analyzing the volatility of American Tower Corp stock returns. The analysis is divided into three main sections:

1. **Data Description**: 
   - Exploration of the data using summary statistics and simple plots to understand the underlying structure and distribution of the stock returns.
  
2. **In-Sample Fit**: 
   - Six different econometric models are fitted and evaluated for their ability to capture the volatility of stock returns.
  
3. **Forecasting Performance**: 
   - Out-of-sample forecasting performance is compared using both rolling and expanding window forecasting schemes to assess which models offer the best predictive power.

This project is a part of the Financial Econometrics I course, authored by Pavlína Křenková and Bernhard Brunner. The Jupyter Notebook can be found in the repository's code folder.

## Installation

To run this project, you need R version 3.5.0 or higher, and the following packages should be installed:

```R
install.packages(c("zip", "ggplot2", "gridExtra", "forecast", "xts", "tseries", "highfrequency", "lmtest", "sandwich", "zoo", "rugarch", "DescTools", "car"))
