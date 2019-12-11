# ml_project
ASHRAE - Great Energy Predictor III

In this project we aim to predict the mean hourly energy consumption of buildings with various energy meter types. Currently, buildings are charged for energy consumption using a "pay for performance" approach where they compare energy usage of building retrofitted with energy efficient technology vs. how much energy it would’ve used without this technology. A model is needed to predict the latter value, and that is what we aim to do in this project. Note that for the purpose of this project we aggregate the data to a mean hourly energy consumption per day as opposed to using the raw hourly values.

Data on energy usage is from Kaggle and can be found at this link - https://www.kaggle.com/c/ashrae-energy-prediction

We fit several different models but found that our best results came from an xgboost model. Using xgboost we were able to predict the mean hourly energy consumption of a building to within 52 kwH.
