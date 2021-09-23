# Deep-Neural-Network-based-Approaches-in-Wind-Time-Series-Forecasting

This respiratory contains the implementation codes of wind-speed prediction in energy forecasting. This study focused on deep neural network based approaches, like the nonlinear autoregressive exogenous inputs (NARX), nonlinear input-output (NIO), and nonlinear autoregressive (NAR) neural network models, in time-series forecasting applications. The idea was to propose NARX neural network based prediction models in wind-speed forecasting for the short-term scheme. The meteorological parameters related to wind time-series (e.g., temperature, pressure, wind speed, wind direction) were analyzed and used to evaluate the proposed models' performance.

## Wind Time Series Data Set
The energy generation depends on weather-related data constraints, including wind speed and direction, pressure, temperature, humidity, etc. In an HRES (hybrid renewable energy system), the records of meteorological values are received from a weather station or a wind firm. In this research, the wind dataset with meteorological values was obtained from the [National Renewable Energy Laboratory (NREL)]( https://www.nrel.gov/grid/eastern-wind-data.html) of the U.S. Department of Energy. 
The distributed wind resource consists of 7 years (2007-2013) data set of pressure, temperature, wind speed and wind direction; where average annual meteorological data were acquired at different surface level. Each data set contains 1 (one) million data samples. The public wind integration data set can be accessed [here]( https://maps.nrel.gov/wind-prospector/?aL=0&bL=groad&cE=0&lR=0&mC=41.80407814427234%2C-95.361328125&zL=4).

## ANN-based Prediction Models
Several deep neural network based prediction approaches have been proposed in the literature were implemented in [MATLAB](https://www.mathworks.com/)  platform, including nonlinear autoregressive exogenous (NARX) model, nonlinear input-output (NIO) model, nonlinear autoregressive (NAR) model, recurrent neural network (RNN) model, and curve fitting neural network (CFNN) model.

## Results
This study investigated the NARX model's performance compared to NIO, NAR, RNN, and CFNN models in forecasting the wind time series. The experimental results included the MSE (mean square error) graphs of the NARX, NAR, and NIO models in the training phase; the WSP (wind speed prediction) results comparisons among NARX, RNN, and CFNN models; the Error-Histogram of the NARX, RNN, and CFNN models; the auto-correlations of the WSP errors of NARX, RNN, and CFNN models; and the input-error cross-correlation of the NARX, RNN, and CFNN models.

