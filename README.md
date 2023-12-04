# Comparative Analysis of Time Series Forecasting Models
## Overview

This repository contains all the materials related to our research project titled "Comparative Analysis of Time Series Forecasting Models: Unveiling the Efficacy of the Prophet Model in Predicting Delhi's Climate Trends". The project aims to evaluate and compare the performance of several time series forecasting models, with a special focus on the Prophet model, in predicting daily climate data in Delhi from 2013 to 2017.

## Data Source
The dataset used in this study is the "Daily Climate Time Series Data" from Delhi, available on Kaggle: [Daily Climate Time Series Data](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data/code?datasetId=312121&sortBy=voteCount). It includes daily observations of key meteorological variables from 2013 to 2017.

## Methods

The forecasting models compared in this study include:

TSLM (Trend, Seasonal, and Cyclical components with Linear Models)
Benchmark methods (Mean, Naïve, Seasonal Naïve, Drift)
ARIMA (AutoRegressive Integrated Moving Average)
Dynamic Regression with ARIMA errors
EWMA (Exponentially Weighted Moving Average)
NNAR (Neural Network AutoRegressive model)
Prophet Model
The effectiveness of these models was evaluated based on their forecasting accuracy for mean temperature data.


## Repository Structure
All the codes are inside "Final_Project.Rmd" and the corresponding pdf contains the results of each procedure.
The folder data is consist of the training set and test dataset.
The folder result includes the accuracy of each model and the finetuned optimal model.
