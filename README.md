# ML-Models-Showcase
This project explores machine learning techniques on two datasets from the UCI Machine Learning Repository:

Iris Dataset 🏵️ - Multi-class classification using various models.
Wholesale Customers Dataset 📊 - Unsupervised clustering using K-Means, Hierarchical Clustering, and DBSCAN.
🚀 Features

1. Classification (Iris Dataset):
Fetches the dataset using ucimlrepo
Preprocesses and standardizes the data
Trains multiple classifiers:
Logistic Regression
Decision Tree
K-Nearest Neighbors
Support Vector Machine
Random Forest
Evaluates models with accuracy, classification reports, and confusion matrices
Visualizes confusion matrices using Seaborn

2. Clustering (Wholesale Customers Dataset):
Applies Exploratory Data Analysis (EDA)
Uses Principal Component Analysis (PCA) for dimensionality reduction
Trains and evaluates:
K-Means Clustering
Hierarchical Clustering (Dendrogram)
DBSCAN (Density-Based Clustering)
Measures clustering performance with Silhouette Score
Visualizes clusters using PCA components

Dependencies:
ucimlrepo
pandas, numpy
sklearn (for ML models and evaluation)
seaborn, matplotlib (for visualization)
scipy (for hierarchical clustering)
