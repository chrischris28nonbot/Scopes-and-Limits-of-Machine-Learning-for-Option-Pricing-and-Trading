# Scopes-and-Limits-of-Machine-Learning-for-Option-Pricing-and-Trading
This is the code base for the models, implementations and results discussed in my Master thesis "Scopes and Limits of Machine Learning for Option Pricing and Trading"

The codes should be run in the following order:
1) Data prep code: prepares the base data from the raw OptionMetric data. Note: because i don't own the data rights, i am not allowed to publish the data
2) Thesis-code_GPU: creates and runs the stochastic volatility models
3) Thesis-code_ML_fulldata_Optuna: pre-runs the machine learning models to find the optimal model parameters
4) Thesis-code_ML_fulldata: creates and runs the machine learning models
5) Thesis-code_ML_stoch-model-cal_Optuna: pre-runs the machine learning models to find the optimal model parameters
6) Thesis-code_ML_stoch-model-cal: creates and runs the stochastic volatility models calibrated by the machine learning models
7) Vol_trading_methods: loads all model outputs and defines and applies the different automated trading strategies
