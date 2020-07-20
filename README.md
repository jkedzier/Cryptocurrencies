# Cryptocurrencies

In this exericise, I used an unsupervised model for analyzing crytocurrencies.

In getting data on crytocurrencies, I needed to cleanse the data.  This involved filtering to currencies actively traded and removing null, incomplete records.

Once cleansed and formatted for machine learning needs, the numbers were scaled to avoid skewing the results due to large numbers in total coins mined, supply, and other metrics.  To cleanse the data created many features, so I employed PCA to narrow down the model to the three most meaningful metrics.

After identifing the most meaningful metrics, I wanted to see what is the most efficient number of clusters using an Elbow Curve.  In doing so, I see that 5 is an effective number.  

To help assess these results, I created a few visualizations, including a 3d plot, a scatter chart, and a data table.
