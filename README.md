# Time Series Darts

## Introduction
The aim of the project is to predict one year sales for each product and store using the last 9 years data. I used a simulated sales time series data with the objective of compare the efficiency and accuracy of each of the models.The data is structured using three distinct approaches, each of which is demonstrated in a separate notebook for easy comparison.

* Darts Model comparison Sales Prices: Create a list of 70 time series, each representing a unique combination of product and store.
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

## Data
DataSet can be found either in the repository or in the link  [DataSet](https://www.kaggle.com/datasets/samuelcortinhas/time-series-practice-dataset)

## Setup
Each Jupyter notebook in this repository can be used to either load a pre-trained model for predictions or modify the code to train a model from scratch and save it locally. To enable training, simply uncomment the relevant sections of the code. Due to GitHub's file size limitations, only a few pre-trained models—Tide, Nhits, and TSMixer—are included. If you wish to train other models, you can uncomment the necessary code and create your own trained models.

## Contact

If you need help with time series and other machine learning projects , I'm available for contracting and fractional work. Feel free to reach out on LinkedIn: [Esther Cifuentes](https://www.linkedin.com/in/est-h-er-cifuentes-83495a331/)
