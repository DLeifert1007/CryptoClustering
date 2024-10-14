# CryptoClustering
In this challenge, cryptocurrencies were classified according to their price fluctuations across various timeframes. Utilizing K-means algorythems and principal component analysis specific price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and one year. 

After preparing the data, I used the elbow method to find the best value for k and then clustered the data based on this. 

Next, the Principal Component Analysis was utilized to reduce the features to three principal components. With this data I used the elbow method to find the best value for k.

Using K-Means with the PCA data, the cryptocurrencies were clustered for best value. In this section I was unsuccessful with creating a scatter plot with hvPlot. I did successfully use plot.scatter instead in order to create my scatter plot in this section. 

Lastly, I determined the weights of each feature or column in order to find the strongest positive and strongest negative influences on each component. Here are my results.

* **Question:** Which features have the strongest positive or negative influence on each component? 
 
* **Answer:** Taking a look at which features have the strongest positive or negative influence on each of the price change percentage over select periods of time components several influences stand out. In feature PC1, the strongest positive influence is on price change percentage over 200 days at 0.594468. This is actually the second strongest influnce of all. The strongest positive influence is in PC3 on seven days with 0.787670. The third strongest influence was seen in PC2 at 0.562182 influencing the 30 day price change percentage. Taking a look at the strongest negative influence we see -0.416728 in PC1 with the 24hour price change percentage. In PC3 we see the second strongest negative influence at -0.361377 with the price change percentage of 60 days. Lastly, the third strongest negative influence is in column or feature PC3 at -0.218795 on the 24 hour price change percentage. Feature PC2 has the strongest negative influence on the one year price change percentage with -0.150789. 