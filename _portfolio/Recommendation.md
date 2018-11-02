---
title: "Recommendation System for Implicit Feedback Dataset"
excerpt: "<br/><img src='/files/images/millionsongs.jpg'>"
collection: portfolio
---

•	Proposed an automated outlier detection scheme that implemented MapReduce Attribute Value Frequency algorithm(AVF) and k-means clustering to expose outliers in numerical, categorical or hybrid datasets. Detected outliers for 50 random dataset without assuming any domain knowledge using Hadoop and Pyspark.
•	Compared the performance for AVF implemented in Spark and MR-AVF(MR paradigm based AVF). Showed that MR-AVF had a much better scaling property and only took O(1) memory.
<!-- 
When I was building a music recommendation system based on implicit feedback using collaborative filtering methods, the optimization for the machine learning model will take too much time if I include every user in the data set in the model. Without significant loss of accuracy, I speed up predicting the preference by applying a much simpler model(popularity model) to predict preference for the user who have listened less than 20 songs. And I apply the collaborative filtering method to the other users.  -->

[Recommendation System for Implicit Feedback Dataset](http://yueqiusun.github.io/files/Recommendation System for Implicit Feedback Dataset.pdf)
