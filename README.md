# Project Overview

In this project, we'll predict the weather using the Facebook prophet algorithm.  Prophet uses an additive model to add up seasonal effects and trends to make a prediction.  The advantage of prophet is that it automatically identifies seasonality in the data - and weather data has strong seasonal effects.  So without any feature engineering, we can get good baseline accuracy.  It can also scale to multiple time series (think data from adjacent weather stations) easily.

By the end, we'll have a model that predicts the weather, and can be extended to improve accuracy.

**Project Steps**
* Load in and clean data
* Define targets and predictors
* Train model
* Scale model to entire dataset using cv
* Make future predictions
