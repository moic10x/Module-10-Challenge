# Module-10-Challenge

This repository includes a python notebook which runs unsupervised learning models to cluster data of several crypto currencies.

## Libraries

This program requires the scikit learn and the hvplot libraries. Program was run on Python version 3.7.

## Procedures

Used the KMeans unsupervised learning model to segment the coins based on the features of the dataset. To determine the number of clusters (the k value) an elbow curve was produced. Once the optimal value of k was determined, we ran the KMeans model on the dataset an produced a scatter plot using hvplot. We also reduced the number of features in the dataset using PCA to 3 components. We created an elbow curve again with the PCA dataframe to determine optimal number of clusters, we created a KMeans model and fitted it to the PCA components, and lastly created a scatter plot. As expected the clusters with the PCA were much tighter than the clusters created with all the features.

