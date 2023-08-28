# Predicting_Credit_Card_Approvals


The goal of this project is to develop a model that can predict whether a credit card application will get approved or not. I used models of machine learning algorithms 
and neural networks to achieve this.

## Dataset

I used the Credit Approval Dataset which is a collection of credit card applications and the credit approval decisions.
The data is available from the <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">UCI Machine Learning Repository</a>.
The dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.

## Data Pre-processing

I performed several pre-processing steps to prepare the data for classification. This included replacing missing values, converting data type, 
scale the features values and feature selection.

## Model Selection and Training

I used lazypredict library to compare the performance of different models and to choose the best one as a baseline model for my task. 
The Ada Boost was the model that has the best results. I also developed a neural network model using TensorFlow. 

## Model Optimization

I used Optuna to tune the hyperparameters of the Ada Boost model and KerasTuner to tune the hyperparameters of the neural network model.

## Results

The best model was Ada Boost tuned who achieved an accuracy of 89% on the test set. 
The model was effective at identifying both classes, achieving an macro average F1 score of 0.89.
