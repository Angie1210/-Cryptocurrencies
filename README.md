# Cryptocurrencies
## Overview

In this project we used *Unsupervised Machine Learning*  to analize a cryptocurrencies dataset to find clusters of coins that shared common features in order to present them as a good option for investment. Resources: Python, Sklearn, Plotly, Pandas, JupyterNotebook and Database: [crypto_data.csv](/crypto_data.csv).

## Results
# Preprocessing data
After cleaning and transforming the data we got the following Dataset to work.

![Screen Shot 2022-06-25 at 9 11 49 AM](https://user-images.githubusercontent.com/43548929/175777269-9b2219c0-da19-48f6-8dea-d5b156978f42.png)

# KMeans
We create an elbow curve to find the best value for K.

![Screen Shot 2022-06-25 at 9 13 14 AM](https://user-images.githubusercontent.com/43548929/175777322-62096611-06c6-414e-ac53-319053e075d4.png)

Decided to use 4 clusters and assigned each coin to a cluster, creating a new DataFrame

![Screen Shot 2022-06-25 at 9 15 13 AM](https://user-images.githubusercontent.com/43548929/175777418-f2e2df20-ff3f-4297-a541-c0e467840651.png)

# Visualizing Cryptocurrencies Results in 3D

![Screen Shot 2022-06-25 at 9 16 02 AM](https://user-images.githubusercontent.com/43548929/175777464-e3ebafe4-c63c-4215-9091-05597cc5bf9c.png)

# Create a table with tradable cryptocurrencies.

![Screen Shot 2022-06-25 at 9 18 54 AM](https://user-images.githubusercontent.com/43548929/175777574-7dc3ebd5-f1cd-4317-85cb-50fee3b488f6.png)

# Visualizing Tradable cryptocurrencies 

![Screen Shot 2022-06-25 at 9 20 02 AM](https://user-images.githubusercontent.com/43548929/175777608-6a2cac8f-0818-471b-bdcc-f92b6365224d.png)

## Summary
The total number of tradable cryptocurrencies is 532. There are divided in 4 c clusters, most the cryptocurrencias are part of Class 3 and Class 0, we have to analyze each group to find which one has the best performance and represents the best option for our group of investors.
