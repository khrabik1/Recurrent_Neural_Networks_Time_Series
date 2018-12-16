# Time_Series
Using Time Series &amp; LSTM to predict temperature


Homework Assignment Final Project: Time Series 
Depaul University 
CSC 578 Neural Networks and Deep Learning
Professor Noriko Tomuro
Fall 2018


The task of the competition is to predict the temperature at the next hour
given the weather conditions and temperature for prior hours. This is
a multivariate time series forecasting problem using a neural network.

The dataset (climate_hour.csv) is described on the Kaggle site 
(https://www.kaggle.com/c/csc578f18-finalproj/data). In this dataset, 14 
different quantities (including air temperature, atmospheric pressure, and
humidity) were recorded every 10 minutes. The original dataset goes back to
2003, but we use a subset for this competition, from 2009 to 2016 (both
inclusive).
We further reduce the set to a version in which recordings are kept for every
hour (rather than every 10 minutes).

Explore various neural networks to solve the problem.

You can also try doing feature engineering, by transforming data or dropping
features.

Considerations:
-	You should probably normalize data values before training, because
	the weighted sum is susceptible to values of different magnitudes
	and/or ranges. After training with normalized data, you have to bring
	the network prediction values back to original scale

