# CryptoClustering

In this assignment, I used Pandas to predict if cryptocurrencies are affected by 24hrs or 7-day price changes. 
I used the DataFrame created from the provided CSV files to code. 
    o	I used the StandardScalar() module from scikit-learn to normalize the data
    o	I created a DataFrame with the scaled data 
    o	Using the Elbow method, I created a dictionary with data to plot the Elbow Curve.
    o	From the Elbow Curve, I predicted the cluster Cryptocurrencies with K-means using the optimal value of k.
    o	I also made another prediction for the cluster Cryptocurrencies, using PCA data on the original Scaled DataFrame.

Finally, I created a composite line plot and scatter chart to contrast the Elbow curves and the Clusters from the original Data and PCA.
