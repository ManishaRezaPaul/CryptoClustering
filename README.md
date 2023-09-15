# unsupervised_learning_challenge

In this module challenge, we will use our knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

To do so, we need to conduct the following steps:

1. Prepare the data
2. Find the best value for k using the original scaled dataframe
   - Create a for loop to compute the inertia with each possible value of k.
   - Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
3. Cluster cryptocurrencies with K-means using the original scaled data
4. Optimize clusters with Principal Component Analysis (PCA)
5. Find the best value for k Using the PCA data
   - Create a for loop to compute the inertia with each possible value of k.
   - Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
6. Cluster cryptocurrencies with K-means using the PCA data
