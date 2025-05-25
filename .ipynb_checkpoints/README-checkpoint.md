# Crypto Clustering

## Overview

This project involves clustering cryptocurrency data using K-Means and Principal Component Analysis (PCA). The goal is to segment cryptocurrencies based on performance metrics and visualize the results using hvPlot. The project demonstrates how to preprocess, scale, reduce dimensionality, and apply clustering to financial datasets.

---

## Features

- Data preprocessing and normalization with `StandardScaler`
- K-Means clustering with elbow method to determine optimal `k`
- Dimensionality reduction using Principal Component Analysis (PCA)
- Cluster visualization using `hvPlot` for both original and PCA-reduced data
- Comparison of clustering results before and after PCA

---

## Technologies Used

- Python 3.x
- Pandas
- Scikit-learn
- hvPlot
- Matplotlib
- Jupyter Notebook

---

## File Structure

crypto-clustering/
│
├── Crypto_Clustering.ipynb          # Main Jupyter Notebook with all steps
├── crypto_market_data.csv           # Input data file
├── README.md                        # Project documentation
└── requirements.txt                 # List of dependencies

---

## How To Use
1. Open the Crypto_Clustering.ipynb notebook.
2. Load and explore the crypto_market_data.csv dataset.
3. Normalize the dataset using StandardScaler.
4. Use the elbow method to determine the optimal value for k.
5. Perform K-Means clustering and visualize the clusters.
6. Apply PCA to reduce the dataset to 3 dimensions.
7. Repeat the elbow method and clustering using the PCA-transformed data.
8. Compare results and answer the key questions in the notebook.

---

## Questions Answered

1. What is the best value for k based on the original and PCA-reduced data?
2. What is the total explained variance of the three principal components?
3. What is the impact of using fewer features for clustering?

---

## Visualizations
- Elbow curves for determining optimal k
- Cluster scatter plots using:
      price_change_percentage_24h vs price_change_percentage_7d
      Principal Components PC1 vs PC2
- Composite plots to compare clustering results before and after PCA

---