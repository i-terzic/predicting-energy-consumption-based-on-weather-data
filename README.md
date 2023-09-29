# Energy consumption prediction 
Predicting energy consumption based on weather data.

## Prediction using an self-trained Machine Learning Model (i guess)
The objective of this project is to build a ML-Model order to predict
energy consumption based on weather data.
It should teach me the fundamentals of machine learning in order to be able
to build a hate speech recognition framework for bachelor thesis.

### Setup
Create virtual enviroment using [anaconda](https://www.anaconda.com/).
```bash
conda env create -n weather-prediction -f ./env.yml
```

After creating the virtual environment you can activate it running the following
command.
```bash
conda activate weather-prediction
```

**Note:** You can also use `anaconda-navigator` in order to import the `env.yml` 
file an create the virtual environment using the GUI.

## Project Info

### What are my goals?
The objective is to build a working ML-Model which will be able to take
weather data as input and predict the energy consumption in a household based
on the provided weather data. Metrics that will be taken into account are not 
yet clarified.

### What to expect?
tbd.


### Thinking Progress
- [ ] Find suitable datasets (~ around 60_000 entries should be enough)
  - [ ] Limit energy consumption & weather data to a specific geological location.
  - [ ] Find data with limited level of complexity.
- [ ] Find matching Regression (i assume) algorithm/model in order to predict 
        consumption level.
- [ ] Review performance of the prediction.
  - [ ] bad prediction performance occurs, evaluate other models or consider 
        building a neural network.


## Changelog
31.08.2023 - development start
06.09.2023 - add [data sets](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather) kaggle
29.09.2023 - feat(data): pre-process data to implement `Vector Autoregression`
