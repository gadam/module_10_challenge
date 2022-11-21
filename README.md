# An Approach to Assembing Crypto Portfolios

This project uses unsupervised learning to assemble price data of several crypto currencies across seven time periods.  

![Original crypto data](./Images/original_crypto_data.png)

It then attempts to segment the data using the seven features via the `K-means` algorithm and the `elbow` method.

![K-Means Elbow](./Images/kmeans_elbow.png)
![Segmented Original via K-Means](./Images/segmented_k_meand_original.png)

Finally it performs a feature reduction via the `Principal Component Analysis` algorithm to arrive at an optimum number of features and confirms that the feature reduction has not been performed at the cost of reducing the available information in the dataset.

![Combined segmented plots](./Images/combined_segment_plots.png)
![Combined segmented plots](./Images/combined_segment_plot2.png)
![Combined segmented plots](./Images/combined_segment_plot3.png)