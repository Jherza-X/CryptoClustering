# CryptoClustering
Module 19 Challenge, UofT Data visualization Bootcamp
Student name: Jesus Hernandez

## Cryptocurrency Market Data Clustering
### Overview
This project focuses on clustering cryptocurrency market data to identify patterns and group similar cryptocurrencies. The analysis involves using K-Means clustering with and without PCA (Principal Component Analysis) to compare the results.

* Key Components
    Data Loading and Preprocessing: Cryptocurrency market data is loaded from the "crypto_market_data.csv" file.Data preprocessing includes handling missing values and scaling features.
    
    K-Means Clustering: The original data is clustered using the K-Means algorithm. Elbow curve analysis is performed to determine the optimal number of clusters.
    
    Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the data. K-Means clustering is then performed on the PCA-transformed data. Elbow curve analysis is again used to identify the optimal number of clusters.

    Visualization: Visualizations include scatter plots and line charts to illustrate clustering results and Elbow curves.
