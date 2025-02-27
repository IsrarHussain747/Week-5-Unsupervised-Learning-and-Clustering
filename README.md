K-Means Clustering with PCA
This project demonstrates the application of K-Means Clustering on a synthetic dataset, along with Principal Component Analysis (PCA) for dimensionality reduction. The objective is to perform unsupervised learning, identify clusters, and visualize the results effectively.

Project Overview
K-Means Clustering: We apply K-Means with three clusters to the dataset.

Elbow Method: Used to determine the optimal number of clusters by analyzing the inertia values.

PCA: Dimensionality reduction to visualize the dataset in two principal components.

Dataset
Ensure the dataset (synthetic_dataset.csv) is available in the specified directory. The dataset should contain at least two features: Feature 1 and Feature 2.

Requirements
Make sure to install the following libraries before running the code:

pip install pandas matplotlib scikit-learn
Project Structure
|-- synthetic_dataset.csv
|-- kmeans_pca.py
|-- README.md
Usage
Clone the repository:

git clone https://github.com/your-username/kmeans-pca.git
cd kmeans-pca
Run the script:

python kmeans_pca.py
Output
K-Means Clustering Visualization: Displays a scatter plot of the clusters and centroids.

Elbow Method Plot: Helps determine the optimal number of clusters.

PCA Visualization: Shows the dataset reduced to two dimensions.

Explanation
K-Means Clustering: Partitions the dataset into k clusters.

Inertia: Measures the sum of squared distances to the closest cluster center.

PCA: Reduces dimensionality while preserving variance, aiding visualization.
