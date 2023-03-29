# K-Means-Clustering-Algorithm-ML
K-Means clustering is a popular unsupervised machine learning algorithm used to group similar data points together in a dataset. The algorithm aims to partition a given dataset into K clusters where each point belongs to the cluster whose mean is closest to it.

Algorithm Steps:
Choose the number of clusters K.
Select K random points from the dataset as initial centroids.
Assign each data point to the nearest centroid, forming K clusters.
Compute the mean of each cluster and use it as the new centroid.
Repeat steps 3 and 4 until convergence is reached. Convergence occurs when the assignments no longer change.
Formula:
The objective function of K-Means clustering is to minimize the sum of squared distances between data points and their assigned centroids. This can be written as:

minimize J = ∑i=1 to n ∑j=1 to k || xi - mj ||^2

where n is the number of data points, k is the number of clusters, xi is the ith data point, and mj is the jth centroid.
