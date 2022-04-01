# spatial_project
Analysis of Spatial Data and Images-course final project

We Predict COVID-19 Cases in Finland using spatiotemporal variables.

Advice for what code is important:
1. [The data preparation script](https://github.com/DanJar96/spatial_project/blob/main/scripts/data_preparation.ipynb) - this script was used to prepare the data for the predictive exercise.

2. [The prediction work script for one time lag](https://github.com/DanJar96/spatial_project/blob/main/scripts/prediction_work_onelag.ipynb) - this script was used to fit and predict using the XGBRegressor model and one period time lagged independent variables.

3. [The prediction work script for multiple time lags](https://github.com/DanJar96/spatial_project/blob/main/scripts/prediction_work_multilags.ipynb) - this script was used to fit and predict using the XGBRegressor model and multiple period time lagged independent variables.

4. [THe prediction interval generation for one time lag](https://github.com/DanJar96/spatial_project/blob/main/scripts/xgb_prediction_intervals.ipynb) this script was used to create the prediction intervals for our model output.
