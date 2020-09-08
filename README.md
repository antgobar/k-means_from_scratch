# k-means_python
python implementation of k-means clustering algorithm in 2D

Current progress: creating functions to make data points and initial centroids.

k-means algorithm: define k subsets (clusters) of points within a set of points which are defined to be in the same cluster

Given a set of points in 2D space, how are k clusters of points defined? Where k is the user defined number of clusters.

First k-points are defined. All distances from the data-points are measured to the k-points.
A data-point is assigned to a k-point if it is closer to that k-point than the other k-points.
Once all data-points have been assigned you have your initial clusters.

For each cluster a centroid is calculated. 
The centroid becomes the new k-point and the process is repeated until there is no further change in the assignement of data-points to k-points.
Then the final assignements should represent the k clusters present in the data.
