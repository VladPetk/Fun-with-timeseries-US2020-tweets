# Fun With Time Series
This repository contains an IPython notebook that explores various machine learning approaches to estimating time series. I test these approaches on a dataset of [24 million tweets about the 2020 US election](https://ieee-dataport.org/open-access/usa-nov2020-election-20-mil-tweets-sentiment-and-party-name-labels-dataset), trying to predict tweet sentiment (estimated using VADER) and retweet count over time.
## Approaches used
#### Single output models
 - Linear estimation
 - Dense neural networks (DNN)
 - Convolutional neural networks (CNN)
 - Long Short Term Memory networks (LSTM)
 #### Multi output models
 - LSTM
 - Residual LSTM
 #### Multi-step multi-output models
 - CNN
 - LSTM
 - Autoregressive (AR) LSTM

## Other Details
The code is very modular, so it's easy to try any specific approaches on your own data. The script also includes code for comparing the effectiveness (MSE) of different approaches on the same data. Finally, visualizations are also included. 
  
