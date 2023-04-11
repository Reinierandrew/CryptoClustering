# CryptoClustering
 
I will use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

I normalised the data using standardscaler from scikit and from the elbow results determined that creating 4 clusters is most effective. The output looking at the 24 hour and 7 day features is:

![scatterplot](https://user-images.githubusercontent.com/112833174/231312565-69685c13-d352-489f-a2d3-7a58dc093128.png)

I then looked at a PCA clustering where again the elbow curve indicated that 4 clusters is most effective. The output is:

![pca_scatter](https://user-images.githubusercontent.com/112833174/231312587-e5ecd9bd-f1f7-415a-b6e5-76d5ef3bec5a.png)

From the above it is clear that reducing the features using PCA results in tighter clusters, therefore increasing the stability and a clearer separation of the clusters
