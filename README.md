# Propensity-Based-Model
## Purchase Propensity Modelling

This project is an attempt to build a Purchase propensity based model using UCI data set. Perform Exploratory data analysis on the data, clean the data, balance the dataset and divide the dataset into test and train. Finally, apply different classification algorithms on test and train to come up with the best classification algorithm for our use case.

## Dataset Link:
http://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset# 

## Classification Algorithms
In our project we have used 5 classification algorithms:
1) Logistic Regression CV (AUC: 89.93% , Recall: 58.36%)
2) Support Vector Classifier (AUC: 83.03% , Recall: 27.32%)
3) Random Forest (AUC: 91.77% , Recall: 57.29%)
4) **Gradient Boosting (AUC: 98.88% , Recall: 91.09%)**
5) Extreme Gradient Boosting (AUC: 97.77%, Recall: 87.98%)

As we can see from above Gradient Boosting algorithm has given us the best results and we have used this Algorithm for our model to predict the propensity of our customers.

## Web Application
I have created a web Application on flask for which I have considered Gradient Boosting Algorithm as the primary model at the backend to perform the prediction. Below is the screenshot of the UI of the web application.  
UI of Web Application
![image](https://user-images.githubusercontent.com/68136798/92538165-9c571d80-f203-11ea-9a7b-a2c30a492849.png)

First Output of Web application
![image](https://user-images.githubusercontent.com/68136798/92538309-f6f07980-f203-11ea-800c-62dabe7bca8e.png)

Second Output of Web application
![image](https://user-images.githubusercontent.com/68136798/92538343-08d21c80-f204-11ea-8e99-8482771c6216.png)

## References
https://github.com/krishnaik06/Deployment-flask
