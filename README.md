K-Means Clustering Implementation
This project implements the K-Means clustering algorithm from scratch in Python. It demonstrates clustering on a 2D dataset and includes visualization.
Features
Custom K-Means algorithm implementation
Data preprocessing with Min-Max scaling
Clustering visualization for k=2 and k=3
Euclidean distance calculation
Usage
Ensure you have numpy, matplotlib, and pandas installed
Place your dataset in a CSV file named "DATA.csv"
Run the script to see clustering results
How it works
The algorithm randomly initializes centroids, assigns data points to the nearest centroid, updates centroids, and repeats until convergence or max iterations13.
Future Improvements
Implement elbow method for optimal k selection
Add more distance metrics
Enhance visualization options
