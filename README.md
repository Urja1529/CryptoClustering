# CryptoClustering

In this challenge, I’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Data set Used

crypto_market_data.csv market data of different cryptocurrencies during different time periods
![](https://github.com/Urja1529/CryptoClustering/blob/main/Output%20Screenshots/Screenshot%202023-09-09%20at%2010.13.24%20AM.png)
# Prepare data

In order to prepare data I have used Standard scaling method and used elbow-method to find optimal number of cluster for  K-Means model
![](https://github.com/Urja1529/CryptoClustering/blob/main/Output%20Screenshots/Screenshot%202023-09-09%20at%2012.23.59%20AM.png)


![](https://github.com/Urja1529/CryptoClustering/blob/main/Output%20Screenshots/Screenshot%202023-09-09%20at%2012.24.12%20AM.png)

# Optimize Clusters with Principal Component Analysis

Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

![](https://github.com/Urja1529/CryptoClustering/blob/main/Output%20Screenshots/elbow%20curve%20with%20PCA.png)

![](https://github.com/Urja1529/CryptoClustering/blob/main/Output%20Screenshots/Scatter%20with%20PCA.png)
