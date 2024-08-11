## Data challenge EM

### The repo contains the following notebooks and code: 
- 1 TimeseriesAnalysisAndUnderstanding.ipynb that helps with understanding the data

- 2 MultivariateInsampleForecasting_with_VAR.ipynb that contains the forecasting model and the walk forward validation.

- 3 RunCode.ipynb notebook that runs the code contained in the 

- 4 functions.py which contains simple and well documented functions to be called from RunCode.ipynb or anywhere else.   

### The approach presented here is quite simple just like the statistical model itself. Other, more sophisticated models, based on machine learning could have had a better performance. The functional approach into building the code is also very simple even though an OOP one could have offered more elegance and better scaling. 

### The performance metric that I chose is MAPE (Mean Absolute Percentage Error) and I motivate the choice inside the comments in the model notebook.

### This work could have been improved by:

- Studying the data a bit better and understanding it in depth

- Testing different models both statistical and machine learning ones. 

- Time series indexing and matrix profile method could have helped to spot patterns in the data.

- Maybe a univariate approach would be worth trying. For example decomposiing the time series, performing forcasts on each component(trend, seasonal, residual) and then putting together the single forcasts at the end.  

- Could be worth studying the data jointly with other time series in order to determine if one time series can predict another's future values, also called Granger causality.

