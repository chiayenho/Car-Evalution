# Car-Evalution

In this project, I build classification models to predict the evaluaion of the car based on their characteristics.
This dataset has 1728 records, each record representing a car evaluation. Each car evaluation is described with 7 attributes. 6 of the attributes represent car characteristics, such as buying price, price of the maintenance, number of doors, capacity in terms of persons to carry, the size of luggage boot, and estimated safety of the car. The seventh variable represents the evaluation of the car (unacceptable, acceptable, good, very good).

First, I applied Nested Grid Search CV technique to final out the best model among decision tree, logistic regression, KNN, Naive Bayes, and SVM. 
'dt': 0.95
'lr': 0.90
'knn': 0.83
'gnb': 0.80
'svm': 0.99
SVM model performs the best among all 5 models.
Then, I used SVM as my final model and trained another model to get the best hyperparameter. The accuracy is 99%. The model only gets 2 incorrect among 346 datapoints in testing dataset.

To get more information about the dataset: 
https://archive.ics.uci.edu/ml/datasets/car+evaluation
