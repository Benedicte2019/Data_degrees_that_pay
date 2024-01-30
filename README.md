# Data_degrees_that_pay
Which college majors will pay the bills?

Wondering which engineering degree have higher mid career prospects? This project uses data collected from a year-long survey of 1.2 million people with only a bachelor's degree by PayScale Inc., made available at http://online.wsj.com/public/resources/documents/info-Degrees_that_Pay_you_Back-sort.html?mod=article_inline by the Wall Street Journal for their article Ivy League's Big Edge: Starting Pay. After doing some data clean up, we'll use techniques for determining the optimal number of clusters, apply a k-means clustering analysis, and visualize the results.

Steps

1. Import libraries
2. Load data and clean
3. Scale features to be used for clustering and append the scaled features to df
4. Subset dataset for clustering
5. Use elbow method to determine optimal number of clusters
6. Generate cluster centers
7. Assign labels to clusters
8. Plot
