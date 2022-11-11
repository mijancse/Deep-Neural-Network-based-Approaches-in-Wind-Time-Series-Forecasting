# Deep-Neural-Network-based-Approaches-in-Wind-Time-Series-Forecasting

This respiratory contains the implementation codes of wind-speed prediction in energy forecasting. This study focused on ANN based prediction models, such as nonlinear autoregressive exogenous inputs (NARX), nonlinear input-output (NIO), and nonlinear autoregressive (NAR) neural network models. The idea was to propose ANN based models in wind time series forecasting for the short-term basis. The time series related variables (e.g., temperature, pressure, wind speed, wind direction) were analyzed and used to evaluate the proposed models' performance.

## Wind Time Series Data Set
Wind power production depends on several data variables, like wind speed, pressure, temperature, humidity, etc. The data records are acquired from a wind farm or other sources. In this research, the dataset was received from the site of [National Renewable Energy Laboratory (NREL)]( https://www.nrel.gov/grid/eastern-wind-data.html). 
Their data resource includes seven years of average annual values of pressure, temperature, wind speed, and wind direction acquired at different surface levels. The public wind integration data set can be accessed [here]( https://maps.nrel.gov/wind-prospector/?aL=0&bL=groad&cE=0&lR=0&mC=41.80407814427234%2C-95.361328125&zL=4).

## ANN-based Prediction Models
Several deep neural network based prediction approaches have been proposed in the literature were implemented in [MATLAB](https://www.mathworks.com/)  platform, including nonlinear autoregressive exogenous (NARX) model, nonlinear input-output (NIO) model, nonlinear autoregressive (NAR) model, recurrent neural network (RNN) model, and curve fitting neural network (CFNN) model.

## Results
This study investigated the NARX model's performance compared to NIO, NAR, RNN, and CFNN models in forecasting the wind time series. The experimental results included the MSE (mean square error) graphs of the NARX, NAR, and NIO models in the training phase; the WSP (wind speed prediction) results comparisons among NARX, RNN, and CFNN models; the Error-Histogram of the NARX, RNN, and CFNN models; the auto-correlations of the WSP errors of NARX, RNN, and CFNN models; and the input-error cross-correlation of the NARX, RNN, and CFNN models.

## Contact
Prof. Dr. Md. Mijanur Rahman, Department of Computer Science and Engineering, Jatiya Kabi Kazi Nazrul Islam University, Trishal, Mymensingh, Bangladesh. Email: mijan@jkkniu.edu.bd

## Citation
Md. Mijanur Rahman, "Deep Neural Network based Approaches in Wind Time Series Forecasting", Github Repository, September 2021. https://github.com/mijancse/Deep-Neural-Network-based-Approaches-in-Wind-Time-Series-Forecasting

## Paper Citation
Rahman, M.M., Shakeri, M., Khatun, F. et al. A comprehensive study and performance analysis of deep neural network-based approaches in wind time-series forecasting. J Reliable Intell Environ (2022). https://doi.org/10.1007/s40860-021-00166-x


