# Cryptocurrencies Unsupervised Machine Learning

## Overview:
My goal was to clean the data crypto data and then analyze it with unsupervized machine learning. Transforming, Fitting, clustering, and visualizing were the keys to making this all sucessful. Our main goal was to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for potential new investments.

## Some tools used:
1. **Pandas**
2. **Hvplot**
3. **Sklearn**
4. **Google Colab**
5. **Jupyter Notebook**
6. **Plotly**

## The Visuals:
![Elbow](https://github.com/Aceofhearts1/Cryptocurrencies/blob/main/Images/Elbow_Curve.png)

The elbow curve graph shows us that the best number of clusters would be 4 and maybe 5. The most dramatic angle change seems to come at 4, so we will use that as our cluster number for the KMean!

![3dscatter](https://github.com/Aceofhearts1/Cryptocurrencies/blob/main/Images/3dScatter_PCA.png)

This 3d graph gives us a good view of our data after being transformed. This is where we will see if our PCA and Cluster values are good enough to work with. We see that the clusters look good. There aren't multiple colors in the wrong clusters. It seems that we have transformed and fit our data properly.

![Results](https://github.com/Aceofhearts1/Cryptocurrencies/blob/main/Images/CryptoCurrency_results.png)

Our final results. We were able to classify different cryptocurrencies for easier analysis for investments with machine learning.
