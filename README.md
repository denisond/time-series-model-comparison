# time-series-model-comparison
This repo contains IPython notebooks modeling Apple stock price data with machine learning, deep learning, and classical time series models.

1. ### [tuned_model_comparison.ipynb :](https://nbviewer.jupyter.org/github/denisond/time-series-model-comparison/blob/master/tuned_model_comparison.ipynb)
EDA and comparing performance of classical time series models (e.g. Exponential smoothing, SARIMA) and deep learning models (e.g. NN, CNN, LSTM) on Apple stock price forecasting problem.

We fit the models in order of increasing complexity. Before moving on from a model we will try to optimize it using a hyperparameter grid search, after which the model will become our benchmark that will need to be passed by more sophisticated models.

2. ### [feat_engineer_regress_models.ipynb :](https://nbviewer.jupyter.org/github/denisond/time-series-model-comparison/blob/master/feat_engineer_regress_models.ipynb)

Featuring engineer/selection for various regression models
