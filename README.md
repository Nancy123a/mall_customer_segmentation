# mall_customer_segmentation
This project utilizes clustering algorithms such as K-Means, DBSCAN, and Affinity Propagation to identify customer segments in a mall based on factors like annual income, age, and spending score.

Here’s a brief overview of each of the clustering algorithms mentioned:

### 1. **K-Means Clustering**
- **Overview**: K-Means is a popular partition-based clustering algorithm. It partitions the data into a predefined number of clusters (k), with each data point assigned to the cluster with the nearest mean (centroid).
- **How It Works**: The algorithm iteratively updates the centroids of clusters by minimizing the sum of squared distances between data points and their respective cluster centroids.
- **Strengths**: Efficient for large datasets and works well when clusters are spherical and of similar sizes.
- **Limitations**: Requires specifying the number of clusters in advance and can be sensitive to the initial placement of centroids.

### 2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- **Overview**: DBSCAN is a density-based clustering algorithm that groups together points that are closely packed, while marking points that lie in low-density regions as outliers.
- **How It Works**: It works by identifying core points (with a minimum number of neighboring points within a certain radius) and expanding clusters from these points. Points that don’t belong to any cluster are labeled as outliers.
- **Strengths**: Can find clusters of arbitrary shapes and is robust to noise (outliers).
- **Limitations**: Requires careful tuning of parameters (radius and minimum points) and may struggle with clusters of varying densities.

### 3. **Affinity Propagation**
- **Overview**: Affinity Propagation is a clustering algorithm that identifies exemplars (representative data points) and forms clusters based on the similarity between data points and their exemplars.
- **How It Works**: The algorithm exchanges messages between data points to determine the best exemplars, with clusters forming around these exemplars.
- **Strengths**: Does not require the number of clusters to be specified in advance and can handle complex cluster structures.
- **Limitations**: Computationally intensive and may be sensitive to input parameters, such as the preference value which influences the number of clusters.

Each of these algorithms has unique strengths and is suitable for different types of data and clustering scenarios.
