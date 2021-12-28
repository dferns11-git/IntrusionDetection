# Intrusion Detection System with ML algorithms

By Darren Fernandes

Referenced the following [GeeksforGeeks post](https://www.geeksforgeeks.org/intrusion-detection-system-using-machine-learning-algorithms/)

Orignal source of [KDD 1999 data](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

In this project I have utilized the KDD dataset to develop an Intrusion Detection System (IDS).
I have cleaned the dataset and have utilized only those features that provide important information for the A.I. algorithm.


The A.I algorthims used in this work are :
1. Decision Tree
2. Random Forest 
3. Naive Bayes.


The code is accessible on the python notebook on this repo.

Random Forest performed the best and I would recommend using this algorithm to develop an IDS. Here are the list of training and test accuracies on the dataset.

| Algorithm      | Training Accuracy | Test Accuracy     |
| :---        |    :----:   |          ---: |
| Decision Tree      | 99.7       | 99.7   |
| Random Forest   | 99.9        | 99.9      | 
| Naive Bayes   | 92.3        | 92.3      | 