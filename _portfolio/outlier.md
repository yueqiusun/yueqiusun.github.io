---
title: "Null and Outlier Detection in Large Datasets"
excerpt: "<br/><img src='/files/images/out1.jpg'>"
collection: portfolio
---


In our project, we design and implement an automated outlier detection schemes without assuming any domain knowledge. In our experiment, our schemes detect outliers for 37 dataset with sizes ranging from 30 obs to millions of obs. 

The data first go through the cleaner. The cleaner cleans data and identifies the suitable technique for automatic outlier detection. 

The categorical data and hybrid data go to Attribute Value Frequency algorithm(AVF). AVF is a method that identifies points with infrequent attributes as outliers. We implement two versions of AVF, one in Spark and  one in Map-Reduce. Both implementation bring the same result and we also compare the performance with respect to time for both versions. We say that MR-AVF to be efficient and available for scaling up because of two main reasons: 1, it takes only O(1) memory, which avoids potential risks like OOM Exception in Spark; 2, we can utilize an arbitrary number of workers in this task, which is important for scalability.

Numerical data is processed by our k-means clustering algorithm. The algorithm first finds the optimal k by looking at WSSSE score. The outliers are then identified as points with largest distance from centroid. 

The innovation of our project is the algorithm design of MR-AVF. The design is novel, efficient and take full advantage of the map-reduce paradigm. It is much faster than the spark version for large datasets and come with the same results.




[Null and Outlier Detection in Large Datasets](http://yueqiusun.github.io/files/Final report_outliers.pdf)
[Null and Outlier Detection in Large Datasets Poster](http://yueqiusun.github.io/files/Poster_outliers.pdf)



