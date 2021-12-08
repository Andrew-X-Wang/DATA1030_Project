#### Note: data is too large to push to GitHub. It can be donwloaded at this link:
https://www.kaggle.com/c/ventilator-pressure-prediction/data

Please refer to the .yml file for up-to-date versions and dependencies. The current Python version should be 3.9.7.

This project is an exploration of the dataset associated with the recent Google Brain - Ventilator Pressure Prediction competition hosted on Kaggle.com. The time-series data provided is from an artificial lung, and the goal is to be able to fit a model given features such as lung compliance, airway restriction, and the timestamp of the taken measurement to predict lung pressure. 

Four models were explored on top of a regression mean-prediction baseline: ElasticNet-penalized linear regression; K-Nearest-Neighbors regression; Random Forest regression; and XGBoost. Model performance is evaluated under the R2-score, and a demonstration of hyperparameter searching followed by the variance and uncertainty of the models. Finally, an exploration of feature importance, both global and local, caps off the technical analysis of this dataset and its fitted models.
