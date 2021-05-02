# Cryptocurrencies

## Project Overview

This project involved the usage of Python and machine learning models to evaluate the different cryptocurrencies based on a dataset provided. The objective is to identify if the provided dataset of cryptocurrencies can be classified using unsupervised learning methods. We used Pandas to pre-process the data before leveraging the K-means method to determine the appropriate number of clusters to be defined using the elbow curve method and then plotting the data on a scatter plot using the hvplot library. We used PCA (principal component analysis) to reduce the number of dimensions that were used to model and we built the model using 3 components PC 1, PC 2 and PC 3.

## Resources
* [Crypto Dataset](https://github.com/dkatragadda/Cryptocurrencies/blob/main/Resources/crypto_data.csv "Crypto Dataset")
* Tools Used: Python 3.7, Jupyter Notebook, Libraries - scikit learn, plotly, hvplot, pandas etc. 

## Results

### Scatter plot of the different tradable cryptocurrencies

![ScatterPlot](https://github.com/dkatragadda/Cryptocurrencies/blob/main/Resources/bokeh_plot_deliverable_4.png)

There were a total of 532 tradable cryptocurrencies in the dataset provided and they were divided into 4 clusters based on the elbow curve that was charted using the K-means algorithm. One notable callout is that 1 of the clusters has a single cryptocurrency BitTorrent and another cluster has 4 cryptocurrencies but the majority of the cryptocurrencies were divided into 2 main clusters based on the three components PC 1, PC 2 and PC 3. 
