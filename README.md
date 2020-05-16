# Kaggle Competition
[ASHRAE - Great Energy Predictor III](https://www.kaggle.com/c/ashrae-energy-prediction/data)

In this project we aim to predict the mean hourly energy consumption of buildings with various energy meter types. Currently, buildings are charged for energy consumption using a "pay for performance" approach where they compare energy usage of building retrofitted with energy efficient technology vs. how much energy it would’ve used without this technology. A model is needed to predict the latter value, and that is what we aim to do in this project. Note that for practical purposes, we predict only the mean hourly energy consumption per day as opposed to hourly meter readings.

We used a host of algorithms to train our models and found that XgBoost gave the best results. Using it, we were able to predict the mean hourly energy consumption of a building with a Median Absolute Error of 52 kwh.

`analysis.ipynb` : combined analysis and modelling codes

`data1.csv`, `data2.csv`, `data3.csv` : daily aggregated data files

`presentation.pdf` : a copy of the presentation that we gave in class

Thanks to Prof. [Brian Spiering](https://github.com/brianspiering) for his guidance and support on this school project. Also, thanks to my teammates [Ash Jha](https://github.com/ash-jha) and [Samarth Inani](https://github.com/samarthinani94) for their contribution.
