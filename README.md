# Spectral Co-Clustering algorithm

This example demonstrates how to generate a dataset and bicluster it using the Spectral Co-Clustering algorithm.

The dataset is generated using the make_biclusters function, which creates a matrix of small values and implants bicluster with large values. 
The rows and columns are then shuffled and passed to the Spectral Co-Clustering algorithm. 
Rearranging the shuffled matrix to make biclusters contiguous shows how accurately the algorithm found the biclusters.

