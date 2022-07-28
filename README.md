# Cryptocurrencies

## Overview of the Project

This project used unsupervised machine learning algorithms such as PCA (Principal Component Analysis), for dimensionality reduction, and K-Means, for clustering, to process and cluster cryptocurrency data for an investment bank.

### Purpose

With the help of PCA and K-Means, the cryptocurrency data is processed, clustered and visualized in this project to help the bank when they will create a cryptocurrency investment portfolio for their customers.

## Results

The project was broken down into four different sections. They are as shown below:

1. The cryptocurrency data was, which was retreived from Crypto Compare, was first preprocessed to make it suitable for the machine learning algorithms. After cleaning the dataset and keeping only relevant features, the dataset was then moved onto the next step.

2. In this step PCA was used to reduce the dimensionality of the data. The features of the dataset was reduced to three principal components.

3. This step performed the clustering of the data. To determine what the K value should be for the dataset, we used the elbow curve as shown below:

image

As we can see from this curve, the elbow bent happens at 4, so we choose K = 4 for the algorithm. After we performed clustering on the data, the results as well as the principal components were added to a DataFrame:

image

4. Data from this DataFrame was then used to visualize the clustering. Here is a 3D image of that:

image

Next we scaled the 'TotalCoinsMined' column and created a new DataFrame with relevant information to create a 2D graph. Here is the DataFrame:

image

Using the data here, we created the 2D graph below:

image

## Summary

To summarize, we collected cryptocurrency data, processed it for our machine learning alrogithms, reduced dimensionality using PCA, used K-Means algorithm to cluster the data and then visualized the performed clustering. This clustering project would assist the investment bank to fill their customer investment portfolio with useful visualizations and analysis.

