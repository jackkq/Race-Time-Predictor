[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jackkq/Race-Time-Predictor/HEAD?urlpath=voila%2Frender%2Fpredictor.ipynb)

# Race Time Predictor

Predict the duration of a training run (i.e. jog) based on gender, distance, elevation gain, heart rate zone and time of day.

## Description

This program allows a user to input key information about a run (gender, distance, elevation gain, heart rate zone and time of day) and will output the predicted duration of this run. The program can thus be used to plan a run for which a distance, and not a duration, is prescribed. The underlying ML model is an Elastic Net Regression model and was trained using Strava data from 116 amateur runners, available on Kaggle [here](https://www.kaggle.com/datasets/olegoaer/running-races-strava). 

## Getting Started

To use the prediction tool, simply click on the Binder badge above (alternatively, click [here](https://mybinder.org/v2/gh/jackkq/Race-Time-Predictor/HEAD?urlpath=voila%2Frender%2Fpredictor.ipynb)). If you are interested in seeing how the model was built, check out the [model_build foler](model_build).

## Author

Jack Quirion\
<jquir073@uottawa.ca>
