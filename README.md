# Cryptocurrencies

The focus of this project was to use unsupervised machine learning to examine cryptocurrency data. The following steps were taken:

* The data was first preprocessed by being cleaned, encoded, and scaled to more appropriately work with the algorithms.
* I used Principle Component Analysis (PCA) to reduce the dimensions of the dataframe, for further analysis.
* The K-means algorithm was used to create an elbow curve plot. This allowed me to find the best value for k, and thus the best number of clusters for the available data.
* Lastly I visualized the data. First I created a 3D scatter plot using the PCA data. Then transformed data for "Total Coin Supply" and "Total Coins Mined", which was used to create a 2D scatter plot.
