# COVID-ARIMA-Forecasting

Project Overview  
This project employs ARIMA modeling to forecast daily COVID-19 cases in Kansas from January 1, 2021, to February 10, 2021. The objective is to use advanced time series analytical techniques to predict the trajectory of COVID-19 cases, providing valuable insights for public health planning.

Data Description  
The analysis is based on a dataset 2020_Covid_Data.xlsx which includes daily COVID-19 case numbers for Kansas among other states. The dataset spans the entire year of 2020.

Methodology  
Data Preprocessing: The data for Kansas is extracted and converted into a time series object, ensuring appropriate frequency for daily data.
Stationarity Testing: Utilizing Augmented Dickey-Fuller Test, the data is tested for stationarity, a key requirement for fitting ARIMA models.  
Model Fitting: Multiple ARIMA configurations are explored:
An automated ARIMA fitting (auto.arima) to identify a suitable starting model.
Manual configuration adjustments based on AICc and BIC metrics, optimizing for the lowest possible values which suggest a better model fit.
Forecasting: Forecasts are generated for 41 days starting from January 1, 2021. Each model's forecast is evaluated and compared using visual plots and summary statistics.

Model Comparison and Selection  
Comparison Metrics: Models are compared based on their AICc and BIC values, and selection is refined using statistical weights derived from these metrics.
Forecast Evaluation: The forecasts are visually represented, and a detailed performance summary is provided for each model, emphasizing the mean forecast values and their respective confidence intervals.

Purpose  
The aim of this project is not only to accurately forecast the immediate future of COVID-19 cases in Kansas but also to illustrate the application of sophisticated statistical models in real-world epidemiological data. The results from this project are intended to assist in understanding the potential spread of the virus and to aid in decision-making processes related to public health.
