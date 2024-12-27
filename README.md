# Unsupervised Machine Learning : Clustering Analysis using Python

## Project Overview

This project focuses on applying unsupervised machine learning algorithms, specifically K-Means, DBSCAN, and Birch, to segment and analyze a trade-related dataset. The analysis will involve determining the optimal number of clusters, characterizing the clusters based on their features, and extracting actionable business intelligence from the identified segments.

## Problem Statement

- The goal of this project is to segment the dataset into distinct clusters based on various trade-related features. This segmentation will help in understanding hidden patterns, relationships, and trends within the data, which can be used for strategic business decision-making. 

 The key objectives are:

-   Identify homogeneous groups (clusters) within the dataset.
-   Analyze and interpret the distinguishing features of each cluster.
-   Provide actionable insights and recommendations based on the clustering results.

## Key Features

-   **Clustering Algorithms**: Implementation of K-Means, DBSCAN, and Birch clustering algorithms.
-   **Cluster Evaluation**: Use of performance metrics like Silhouette Coefficient and Davies-Bouldin Index to assess clustering quality.
-   **Optimal Cluster Selection**: Identification of the optimal number of clusters through algorithm evaluation and hyperparameter tuning.
-   **Cluster Characteristics**: In-depth analysis of cluster profiles and patterns for actionable business insights.
-   **Data Preprocessing**: Handling of categorical and numerical data, with feature engineering for enhanced analysis.

## Dataset

The dataset used in this project is the Import - Export Dataset that contains a total of 15,000 trade transactions, with a sample size of 5,001 rows selected for analysis. Key variables include:

-   **Categorical Variables**: Country, Product, Import/Export, Category, Port, Shipping Method, Supplier, Customer, Payment Terms (nominal and ordinal data).
-   **Non-Categorical Variables**: Quantity, Value, Weight (numerical data).

The data is stored in CSV format and is structured to reflect international trade transactions over time.

## Technologies Used

-   **Programming Language**: Python
-   **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
-   **Environment**: Google Colab
-   **Version Control**: GitHub (for version tracking and collaboration)

## Methodology

1.  **Data Preprocessing**: Data cleaning, encoding of ordinal variables, and scaling of numeric features to prepare the dataset for clustering.
2.  **Clustering**: Application of K-Means, DBSCAN, and Birch algorithms to segment the data into clusters.
3.  **Evaluation**: Use of the Silhouette Coefficient and Davies-Bouldin Index to assess the quality of clusters and select the optimal model.
4.  **Analysis**: Detailed analysis of each cluster to understand the nature of the trade transactions and identify trends.

## Insights and Applications

-   **Cluster Insights**: K-Means, DBSCAN, and Birch produce different insights, with K-Means showing the most distinct clusters based on Quantity and Weight.
-   **Business Applications**:
    -   **Targeted Marketing**: Use Cluster 1 ("Low-Volume Transactions") for promoting budget-friendly products and Cluster 4 ("High-Volume, Low-Weight Transactions") for bulk purchase discounts.
    -   **Inventory Management**: Focus on stocking bulky items for Cluster 3 and lightweight, high-volume products for Cluster 4 to streamline supply chain operations.

## Contributors

-   **Anirudh Gupta**
-  **Amitanshu Tiwari**
