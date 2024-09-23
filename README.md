# Time Series Darts

## Introduction
The aim of the project is to comparison of various time series models using Darts. I used a simulated sales time series data with the objective of predict the number of products sold the next year.
I structure the data with three different approaches, each of them you can see in a different notebook:
* Darts Model comparison Sales Prices: Create a list of 70 time series,each representing a unique combination of product and store.
* Darts Model comparison Sales Prices per Store: Create a list of 7 arrays of time series (one per store), where each array contains 10 time series (one for each product)

* Darts Model comparison Sales Prices per Product: a list of 10 arrays of time series (one per product), where each array contains 7 time series (one for each store).

Each notebook has a comparison of the models LGBM, TFT, TiDE,N-BEATS,TSMixer and NHits.
You can find more information about the project in the [blog post]()

## Requirements

* Python version Python: 3.10.12
* Jupiter version: 6.5.6
* AutoViz version: 0.1.804
* Darts version: 0.29.0
* Tensorboard version: 2.15.1

## Setup
Every Jupiter note can either use a trained model or change the code to train the model save it and make predictions. In order to achieve this, you will need to uncomment some part of the code. It is specified in each notebook.

## Contact

My LinkedIn:[Esther Cifuentes](https://www.linkedin.com/in/esther-cifuentes-70975b1/)
