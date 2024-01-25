This project applies our understanding of the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price fluctuations across various timeframes. Specifically, we will examine price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

We start of by reading a csv file that has the cryptocurrences. Thereafter, we standardize the data using the StandardScaler() module from sci-kit learn. After that we do
1) Find the Best Value for k Using the Original Scaled DataFrame
2) Cluster Cryptocurrencies with K-Means Using the Original Scaled Data
3) Optimize Clusters with Principal Component Analysis
4) Find the Best Value for k Using the PCA Data
5) Cluster Cryptocurrencies with K-Means Using the PCA Data
6) Determine the Weights of Each Feature on Each Principal Component
