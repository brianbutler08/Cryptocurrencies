# Cryptocurrencies

# Project Overview

For this project, we utilized unsupervised machine learning techniques to analyze a set of cryptocurrency data and summarize our findings. The resulting analysis could be used by an investment bank to propose a new cryptocurrency portfolio to its clients.

The primary steps that we took for this analysis included:

- Preprocessing the dataset
- Reducing the data dimension using Principal Component Analysis
- Clustering cryptocurrencies using K-Means
- Visualizing classification results with 2D and 3D scatter plots

# Results

## Clustering Cryptocurrencies using K-Means

In order to identify cryptocurrency clusters, we began by using the K-Means method to generate an elbow curve. The best k-value appears to be 4, leading us to proceed with our analysis with 4 clusters. 

![elbow](https://github.com/brianbutler08/Cryptocurrencies/blob/main/Visualizations/elbow.png)

## Visualizations

After applying PCA to our cryptocurrency dataset in order to reduce the dimensions to three principal components, we generated a 3D scatter plot using Plotly Express.

![3D](https://github.com/brianbutler08/Cryptocurrencies/blob/main/Visualizations/3D.png)

Finally, we summarized our analysis in a final table of tradable cryptocurrencies that could be shared with investors. 

![table](https://github.com/brianbutler08/Cryptocurrencies/blob/main/Visualizations/table.png)

After scaling the appropriate data fields, we generated a scatter plot with "TotalCoinsMined" on the x-axis and "TotalCoinSupply" on the y-axis.

![scatter](https://github.com/brianbutler08/Cryptocurrencies/blob/main/Visualizations/Screen%20Shot%202022-10-12%20at%209.29.51%20PM.png)

# Summary

As a result of this project, we have identified 532 cryptocurrencies, clustered using various unsupervised machine learning algorithms. The report includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment opportunity.


