# Energy consumption prediction 
Predicting energy consumption based on weather data.
In order to predict energy demand based on weather 
consumption two models using [skforecast](https://skforecast.org/) will be developed.
The goal is to use univariate and multivariate Timeseries forecasting with `sklearn`-based 
regression models. Also a comparison between the uni- and mutlivariate approach will be done.

## Setup

This project uses [anaonda](http://anaconda.com/) for project setup. 

### Linux & MacOS

In order to create the virtual environment please execute the following set of 
instructions. 

```console
$ conda env create -f ./env.yml
$ conda env activate weather-prediction
```

**Note**: If some updates are done to `env.yml` you will have to update the 
virtual environment running the following comand.

```console
$ conda env update -f ./env.yml
```

## Notebooks

The repository contains only one `Jupyter-Notebook` with all relevant steps 
including EDA, Pre-Processing, Model-Implementation and -Evaluation. 
