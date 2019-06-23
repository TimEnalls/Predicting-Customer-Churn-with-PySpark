# Predicting-Customer-Churn-with-PySpark



**Libraries Used**

• Pandas === 0.23.4

• Numpy === 1.15.4

• Scikit Learn === 0.20.1

• Matplotlib === 3.0.2

**The Motivation for the Project**

I chose to work on this project for the following reasons:

•	I find the concept of customer churn to be intriguing and most companies view customer churn as a high-priority use case.

•	Spark is an exceptionally high-demand skill in 2019 and using the PySpark package in Python is a great way to familiarize myself with the framework.

•	This project was a great opportunity to familiarize with an industry I never worked in, which is the music service industry. The dataset used in this project mirrors how a dataset might look for a company such as Spotify.

•	Many of the approaches I used in this project are directly applicable to my present and future work projects.

To view additional visualizations regarding this analysis, feel free to visit my Medium post about this analysis:  https://medium.com/@timenalls/how-to-predict-customer-churn-with-pyspark-fb0d30f55253?postPublishedType=repub

**The files in the repository**

I included a python file containing the project. Unfortunately, I could not include other files due to the 25MB file size limitation per repository.

**A summary of the results of the outcome**

Using the data, I answered the following questions:

1.	The **Gradient-Boost Tree model** typically has the highest F1 score in this project. However, each time I train the models in this notebook, the results vary. 

2.	After optimizing the Gradient-Boost Tree model, I ultimately chose the 10 value for max iterations and the 5 value for max depth because of the results from a cross validation. I found that the F1 score increased by **2.2%** to **81.8%** and the accuracy increased by **2.4%** to **79.1%** as a result of optimizing the model.
3.	I displayed the features that were most predictive in the Gradient-Boost Tree model and found that these four features had noticeably higher importance values than the other features: **days_active, NextSong, Thumbs Up, and days_free**. The first three features makes sense because churned users would naturally have lower values for those features than users who decide to use the music service considerably longer.


**Acknowledgements**

The data I used in this analysis was created and provided by Udacity.

