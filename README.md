# choronary-disease-classification
This is a classification problem solution for one of my Data Science assignments
### The goal is classifying coronary heart disease which has two classes of 0 or 1 using several classifiers based on all features in the following dataset: [link](https://raw.githubusercontent.com/tofighi/MachineLearning/master/datasets/heart.csv). 
---
#### The best classifier for the problem is the logistic regression.</br>
Considering our problem which is to predict whether a person has a coronary desease or not it is much more important to predict whether a person has a disease and not whether a person does not have it. <br><br>
![](/conf_matrix.JPG)
</br>
By looking at the confusion matrix above we can see that we have 12 false negatives and 21 true positives which is the best result among all models, some models were better at predicting true negatives but this is not what our model is supposed to do.
