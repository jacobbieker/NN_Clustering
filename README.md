# NN_Clustering
Attempt to replicate results of DBSCAN with a neural network.

# Motivation 
DBSCAN is a great way to do clustering of points, and is used, for example, in the FACT collaboration to clean image of air showers. Currently, I am using DBSCAN to preprocess FACT images, but the limiting factor is how slow DBSCAN is. For example, preprocessing 1 million FACT events takes about an hour and a half if no DBSCAN is used, if DBSCAN is, then the time it takes it measured in months on a 8c/16 thread processor. As an alternative, creating a network that can output similar clustering results would be incredibly helpful. Even if the clustering is not exact, but close, then the results should be fine to use for the project.
