# Forecast of Customer Churn Using Machine Learning



<a href="https://github.com/joshlingy/Forecast-of-Customer-Churn-Using-Machine-Learning/blob/master/Forecast-of-Customer-Churn-Using-Machine-Learning.ipynb">Highly recommended to click this link to see more detail of what I have done about this project!</a>

** Please reload it if something went wrong on the page. **



In this project, I use many supervised learning models to identify customers who are likely to stop using the service in the future. Furthermore, I will analyze the top factors that influence user retention.

* First, let's see the total initial charge for the customers in the dataset. It is a normal distribution

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/total_intl_charge.png">
</p>


* By using the Pearson correlation coefficient to analyze feature importance and rank key features that affect the probability of the churn

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/correlations.png">
</p>

* The use of many algorithms, such as Logistic Regression, K-Nearest Neighbors and Random Forest, for the telecom company to help forecast the churn probability in Python

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/Random-Forest.png">
</p>

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/Logistic -Regression.png">
</p>

* Confusion Matrix (Precision, Recall, Accuracy)
TP: correctly labeled real churn
Precision(PPV, positive predictive value): tp / (tp + fp); Total number of true predictive churn divided by the total number of predictive churn; High Precision means low fp, not many return users were predicted as churn users.
Recall(sensitivity, hit rate, true positive rate): tp / (tp + fn) Predict most postive or churn user correctly. High recall means low fn, not many churn users were predicted as return users.

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/Random-Forest.png">
</p>

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/Logistic-Regression.png">
</p>

* Finally, we can get the ROC curve to evaluate the models.

<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/ROC-Random-Forest.png">
</p>


<p align="center">
  <img src="https://github.com/joshlingy/Telecommunication-Industry-Forecast-of-Customer-Churn/blob/master/graphs/ROC-LR.png">
</p>
