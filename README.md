# Energy consumption prediction 
Predicting energy consumption based on weather data.
In order to predict energy demand based on weather 
consumption two models using <a href="https://skforecast.org/0.11.0/index.html" target="_blank">skforecast</a> 
will be developed.
The goal is to use univariate and multivariate Timeseries forecasting with `sklearn`-based 
regression models. Also a comparison between the uni- and mutlivariate approach will be done.

## Setup

This project uses <a href="https://anaconda.com" target="_blank">anaconda</a>
for project setup.

### Linux & MacOS

In order to create the virtual environment please execute the following set of 
instructions. 

```console
conda env create -f ./env.yml
conda env activate weather-prediction
```

**Note**: If some updates are done to `env.yml` you will have to update the 
virtual environment running the following comand.

```console
conda env update -f ./env.yml
```

## Notebooks

The repository contains only one `Jupyter-Notebook` with all relevant steps 
including EDA, Pre-Processing, Model-Implementation and -Evaluation. 
The dataset was downloaded from [1] and contains the electrical and heat demand 
of a residual building from December 2010 until November 2018 in one-hour steps.
 

## References
[1]   Taheri S, Jooshaki M, Moeini-Aghtaie M. Long-term planning of integrated 
local energy systems using deep learning algorithms. International Journal of 
Electrical Power & Energy Systems. 2021 Jul 1;129:106855. 
DOI: <a href="https://doi.org/10.21227/dfvb-re49" target="_blank">
https://doi.org/10.21227/dfvb-re49</a>
