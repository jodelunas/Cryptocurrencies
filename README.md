# Cryptocurrencies

The focus of this project was to use unsupervised machine learning to examine cryptocurrency data. The following steps were taken:

* The data was first preprocessed by being cleaned, encoded, and scaled to more appropriately work with the algorithms.
* I used Principle Component Analysis (PCA) to reduce the dimensions of the dataframe, for further analysis.
* The K-means algorithm was used to create an elbow curve plot. This allowed me to find the best value for k, and thus the best number of clusters for the available data. Shown below
* Lastly I visualized the data. First I created a 3D scatter plot using the PCA data. Then transformed data for "Total Coin Supply" and "Total Coins Mined", which was used to create a 2D scatter plot. Shown below
<img width="687" alt="Screen Shot 2022-10-05 at 4 06 29 PM" src="https://user-images.githubusercontent.com/106006911/194164012-fc7efb0a-b118-4bf7-8474-577a04be4dd7.png">
<img width="692" alt="Screen Shot 2022-10-05 at 4 06 40 PM" src="https://user-images.githubusercontent.com/106006911/194164038-5a8d2506-9261-442c-b647-8984d94c6177.png">
<img width="668" alt="Screen Shot 2022-10-05 at 4 06 53 PM" src="https://user-images.githubusercontent.com/106006911/194164104-042887ef-1ce2-47e0-bb15-60db4a234bfa.png">
