# kaggle-Don-t-Overfit-II
This is a solution to kaggle's Don't OverfitII competition ,which acheived a score of .872.
this is the link to the competition:
https://www.kaggle.com/c/dont-overfit-ii
The aim of this competition was to develop a model without overfitting. 
Here we first select relevant features through scikits RFECV with L1 regularization.
Then we build a 1 hidden layer neural network using keras.
The input dataset is split into train and validation dataset using Stratified kfold.


