# Unsupervised-Learning
K-Means Clustering on Wholesale Customers Data
This project involves applying K-Means clustering to a dataset of wholesale customers. The objective is to segment customers into distinct groups based on their purchasing behavior. The analysis includes data standardization, clustering with different numbers of clusters, and visualizing the results.

Project Overview

	1.	Data Loading and Preprocessing:
	•	Load the dataset using pandas.
	•	Check for missing values and basic statistics.
	2.	Data Standardization:
	•	Standardize the data using StandardScaler from sklearn.
	3.	K-Means Clustering:
	•	Perform clustering with K-Means for different numbers of clusters.
	•	Evaluate the clustering performance using the elbow method.
	4.	Visualization:
	•	Visualize clusters for different numbers of clusters (3, 4, and 6).
	•	Scatter plots of ‘Milk’ vs. ‘Grocery’ with cluster labels.

Files

	•	Wholesale_customers_data.csv: The input dataset.
	•	kmeans_clustering.py: The main Python script that performs data processing, clustering, and visualization.

Requirements

Make sure you have the following Python packages installed:

	•	pandas
	•	numpy
	•	scikit-learn
	•	matplotlib

Results

The analysis provides insights into customer segmentation based on their purchasing behaviors. The elbow method helps in determining the optimal number of clusters for K-Means clustering.
