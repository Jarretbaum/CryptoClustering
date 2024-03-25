# CryptoClustering
Module 19 Challenge

## Overview
This repository contains code for the Crypto Clustering assignment, where we aim to cluster cryptocurrencies based on market data using K-means clustering and Principal Component Analysis (PCA).

## Summary of Practices
1. **Data Loading and Exploration**: I started by loading cryptocurrency market data from a CSV file into a Pandas DataFrame. I then explored the data by generating summary statistics and visualizing it to understand its structure.

2. **Data Preparation**: I normalized the data using StandardScaler from scikit-learn to prepare it for clustering. This step is crucial for ensuring that features are on a similar scale, which is a requirement for many machine learning algorithms.

3. **Finding the Best Value for k Using the Elbow Method**: I employed the elbow method to determine the optimal number of clusters (k) for our K-means clustering algorithm. By plotting the inertia values for different values of k, I identified the point where the rate of decrease in inertia starts to slow down, indicating the optimal number of clusters.

4. **Clustering Cryptocurrencies with K-means Using Original Data**: I utilized the K-means algorithm to cluster cryptocurrencies based on their features. After fitting the model, I predicted the clusters and visualized them using a scatter plot.

5. **Optimizing Clusters with Principal Component Analysis (PCA)**: I applied PCA to reduce the dimensionality of the dataset while retaining the most relevant information. By examining the explained variance ratio, I assessed how much of the dataset's variance was captured by the principal components.

6. **Finding the Best Value for k Using PCA Data**: Similar to the previous step, I used the elbow method to determine the optimal number of clusters for the PCA-transformed data. This allowed me to identify the appropriate number of clusters considering the reduced feature space.

7. **Clustering Cryptocurrencies with K-means Using PCA Data**: I clustered cryptocurrencies using the K-means algorithm on the PCA-transformed data. By predicting clusters and visualizing them, I assessed how the reduced feature space impacted cluster formations.

8. **Visualizing and Comparing Results**: Finally, I visualized and compared the clustering results obtained from the original data and the PCA-transformed data. This allowed me to observe the impact of using fewer features on the clustering outcome.

All of these techniques are vital in machine learning workflows.

## Stack Overflow Articles
- [How to start machine learning with Python programming](https://stackoverflow.com/questions/38072334/how-to-start-machine-learning-with-python-programming)
- [How do I create test and train samples from one DataFrame with Pandas?](https://stackoverflow.com/questions/24147278/how-do-i-create-test-and-train-samples-from-one-dataframe-with-pandas/24151789#24151789)
- [Stack trace and exception handling in Python](https://stackoverflow.com/questions/12665971/stack-trace-and-exception-handling-in-python)

## Documentations
- [NumPy Documentation](https://numpy.org/doc/)
- [hvPlot Documentation](https://hvplot.holoviz.org/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)


