# cryptoClustering
Unsupervised Machine learning

Overview

This GitHub project focuses on exploring and implementing K-Means clustering on cryptocurrency data. The goal is to find the optimal number of clusters (k) using both the original scaled data and Principal Component Analysis (PCA) data.

Getting Started

To begin, follow the steps outlined below:

Find the Best Value for k Using the Original Scaled DataFrame:
Utilize the elbow method to determine the optimal number of clusters.
Create a line chart visualizing inertia values for different k values.
Answer the question: What is the best value for k?
Cluster Cryptocurrencies with K-means Using the Original Scaled Data:
Initialize and fit the K-means model with the best k value.
Predict clusters and create a scatter plot using hvPlot.
Evaluate the impact of clustering on the original scaled data.
Optimize Clusters with Principal Component Analysis (PCA):
Perform PCA on the original scaled DataFrame and reduce features to three principal components.
Determine the total explained variance of the three principal components.
Create a new DataFrame with PCA data.
Find the Best Value for k Using the PCA Data:
Apply the elbow method on PCA data to identify the optimal k.
Visualize inertia values with a line chart.
Compare the best k value with that of the original data.
Cluster Cryptocurrencies with K-means Using the PCA Data:
Initialize and fit the K-means model with the best k from PCA.
Predict clusters and create a scatter plot using hvPlot.
Evaluate the impact of using fewer features for clustering.

