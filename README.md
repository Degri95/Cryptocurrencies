# Cryptocurrencies
Analyzing cryptocurrencies using Unsupervised machine learning to group data.

## Overview

In this project cryptocurrency data was preprocessed, scaled, and fitted to an unsupervised machine learning model. PCA was applied to the scaled data to reduce dimensions, and the K-Means algorithm was used to group and label the data.

## Results

After the data was preprocessed and scaled, Principal Component Analysis (PCA) was applied to reduce dimensionality from 98 to 3.

![PCA](/Resources/PCA.PNG)

an elbow curve was created to determine how many clusters would best fit the data.

![finding k](/Resources/find_k.PNG)
![elbow curve](/Resources/elbow_curve.PNG)

K-Means was then initialized with 4 clusters and fitted with the PCA data. Once the predictions were created, a new dataframe was created.

![DataFrame](/Resources/dataframe.PNG)

With the class predictions and data all ready, visualizations were created using plotly and hvplot.

![3d plot](/Resources/3d_plot.PNG)
![scatter plot](/Resources/scatter.PNG)