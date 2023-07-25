# Airline Delay Prediction using Classification Algorithms

### Problem Description
       
The number of flights is growing as civil aviation develops, and flight delays are becoming a severe problem that even threatens to become the new normal.
In particular, this work intends to demonstrate that the classification algorithm has advantages in the problem of algorithm selection in machine learning technology.
The four supervised machine learning algorithms are KNN, Random Forest, Logistic Regression, and Support Vector Machines. 
Comparative studies are conducted based on to confirm the efficacy of the suggested method.
The prediction outcomes are thoroughly evaluated using a number of criteria, including Accuracy, Precision, Recall, F1 Score, ROC curve, and AUC Score.
The outcomes demonstrate that the algorithm not only maintained high stability but also enhanced forecast accuracy.



### Analysis Summary        
Flight delays can be expensive for airlines and extremely annoying for customers.
As they result from a variety of factors, such as an increase in air traffic at the origin or destination airport, weather, etc.,
flight delays are difficult to comprehend.
The on-time performance statistics of airline schedules may be helpful in illuminating the reasons for flight delays.

Different days of the week and months have different average arrival delays.
July has the highest average arrival delay on the contrary month November, September, and February have the negative average arrival delay.
August has an average arrival delay of 20 minutes. January and December have an average arrival delay of 10 minutes.
March, June, and October have an average arrival delay of less than 10 minutes.
Day 7 has the highest average arrival delay on the contrary Day five has a negative average arrival delay.
Day 6 and Day 1 have an average arrival delay of 10 minutes. Large distance Origin has less arrival delay as compared to Less distance Origin.
The interval of 0-1000 distance has more high arrival data points than 1000-2000 distance data points.

In essence, my modeling strategy predicts airline delays by employing well-established and well-liked machine learning methods including Logistic Regression, KNN, SVM, and Random Forest.
This analysis has sections for exploring datasets, cleaning up data, drawing conclusions from visualizations, developing and testing classification models, and interpreting models.
Accuracy ratings were calculated using common model assessment measures. 

The objective of this dissertation is to build a model for predicting flight delays using flight on-time performance data,
and then use the model to learn about previous delayed flights.
Even with a somewhat skewed class distribution, accuracy can still be a helpful statistic. 


Accuracy can stop being a trustworthy indicator of model performance when the class distributions are severely skewed.
The typical machine learning practitioner and their presumptions about classification accuracy are to blame for this unreliability.
Predictive modeling for classification is often applied to small datasets when the class distribution is equal or nearly equal.
Since scores above 90% are excellent, generally professionals have the sense that high accuracy scores (or, conversely, low error percentage ) are beneficial.
On an unbalanced classification task, achieving 90 or even 99 percent classification accuracy may be insignificant. 

As a result, classification accuracy intuitions based on balanced class distributions will be used incorrectly, deceiving the practitioner into believing that a model performs well or even well when it actually does not. There is no "most superior algorithm" or "most flexible method" in classification machine learning. Different algorithms must be tested. 
```
