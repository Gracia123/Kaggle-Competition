# Predict the location of a protein given various measurements

This is a multi-class problem with 15 classes related to proteins. Every protein is associated with exactly one class. The goal is to predict the class of ~380 observations (proteins) in the test file. The data are messy, and have missing values. 

Models such as SVM, logistic regression, random forest and MLP/NN, ensembling were used. Each algorithm used K-Fold cross validation for tuning the Hyperparameters. Random Forest outperformed the other models along with MLP/NN, while Ensembling did not result in a better prediction accuracy. 
Thereby, achieving an accuracy of 68% by combining Random Forest classification and Neural Networks (MLP).


# E-commerce product classification

The goal is to classify e-commerce products into 27 categories. The data includes categorical features, a noisy text description and a noisy image for each product. The data consists of e-commerce products. Each product as a unique id and a category. Task is to predict the category of each product based on categorical features, a noisy text description and a noisy image.

Performed noisy text classification with tokenization and LSTM, also did image classification using VGG, thereby achieving an accuracy of 96%.
