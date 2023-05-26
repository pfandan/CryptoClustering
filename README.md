# CryptoClustering
Overview
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

Steps
Load and preprocess the data.
Scale the data using StandardScaler.
Find the best value for k using the elbow method.
Cluster cryptocurrencies with K-means using the original scaled data.
Perform PCA to reduce the features to three principal components.
Find the best value for k using the PCA data.
Cluster cryptocurrencies with K-means using the PCA data.
Visualize and compare the results using hvPlot.
Results
The project includes the following visualizations:
Visualzing DataFrame 
<img width="757" alt="image" src="https://github.com/pfandan/CryptoClustering/assets/43565491/811e5105-5f69-4be4-acf6-a1aef402dc5d">


Elbow curve for the original data.
<img width="734" alt="image" src="https://github.com/pfandan/CryptoClustering/assets/43565491/ac5239b9-5ed6-4a91-8fd7-c3f121989196">


Elbow curve for the PCA data.
<img width="734" alt="image" src="https://github.com/pfandan/CryptoClustering/assets/43565491/76fdebe7-2bdf-4886-9020-a19c478aa46c">


Scatter plot of cryptocurrency clusters based on the original data.

<img width="693" alt="image" src="https://github.com/pfandan/CryptoClustering/assets/43565491/92f3f2bf-2547-4d3a-8cd3-3247105b90c3">


Scatter plot of cryptocurrency clusters based on the PCA data.
<img width="671" alt="image" src="https://github.com/pfandan/CryptoClustering/assets/43565491/12d63077-10fd-478b-a4bc-9b3ad64d07e6">


Conclusion
The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

Dependencies
Python
pandas
NumPy
scikit-learn
hvPlot
