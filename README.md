# Module11_Challenge
Unsupervised Learning using KMeans and PCA

## Project: Module 11 submission

## Description:
### Unsupervised Learning - Learning about the data by exploring the characteristic features and clustering by similarities
- Here we use K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price percent fluctuations across various timeframes.
### Optimal number of clusters - k - is deduced by developing an elbow curve

## Libraries:
        - pandas
        - KMeans, PCA, StandardScaler from scikit-learn


## Input dataset: 
- Contains different crypto currency coins and percent change in price across different timeframes.

## Goal: To use K-Means and Principal Component Analysis to figure out the number of clusters appropriate to this dataset and the material features contributing to the variance.

- PCA is a method to reduce dimensionality (or bring down the number of features) and concentrate on the material ones. This in turn will help us understand the dataset in terms of similarity and groupings as denoted by the clusters.

## Output:
- Deduce number of clusters across the features supplied
- Figure out the explained variance ratio across the 3 Principal Components
- Deduce number of clusters across the PCAs
- Determine the weight (or influence) of each feature on each Principal Component
