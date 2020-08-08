# Predict-Shop-Sales-Timeseries
Exploring timeseries concepts on predicting sales of items in different shops. 

- Kaggle Competition:  https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview
- Kaggle Notebook:  https://www.kaggle.com/swatisk2702/predict-sales-timeseries

Submissions are evaluated by root mean squared error (RMSE). True target values are clipped into [0,20] range.

- Used ADF( Augmented Dicky Fuller Test) to check stationarity of data.
- Explored AR, MA, and ARMA models - find the process of the data using Autocorrelation Function and Partial Autocorrelation Function
- Used Prophet from Facebook for predictions. It's a very promising tool, that is often a very handy and quick solution to the frustrating flatline : Explored ways in which we can apply Prophet for prdictions:
  - Bottom Up 
  -  Middle Out
- Also tried to explore work done in Hierarchical TimeSeries (scikit-hts)
