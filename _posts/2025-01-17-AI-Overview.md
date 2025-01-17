---
title: "Machine Learning"
date: 2025-01-17 00:00:00 +0800
categories: [Machine Learning]
tags: [Machine Learning]
---

#Machine Learning

                            Overview (Workflow of Machine Learning)

Data collection: The most important thing for AI – its lifeblood – is data. We collect the data OR we create the data on the basis of what kind of problem we are really solving. We do have to keep in mind about privacy concerns though. What kind of data is it ? Structured, unstructured, timeseries, static, dynamic. Perform the EDA (Exploratory Data Analysis) by studying the data on your own. This is where domain knowledge comes in handy as you study the data and know that the output should be particularly this/that. 

Data Preparation/Preprocessing: One of the major reasons why machine learning algorithms do not perform well is because of the incomplete data/noisy data. So, after we get the data, we clean it, fill the missing values – which we call the feature imputation. Along with it, encode the features in terms of numbers (aka one hot encoding) for the machine to understand. Something called feature engineering would come next where we transform the data into potentially more meaningful representation by adding in domain knowledge.

Data splitting: Usually into 3 parts: training set (70-80 % of the data), validation set (10-15%) – this is where model hyperparameters are turned, Test set (usually 10-15%) – models final performance is evaluated on this after it is trained on the training set.

Train the model on the data: We then select specific algorithms on the basis of learning i.e. whether it is supervised, unsupervised or reinforcement learning. Choose algorithms on the basis of regression, classification like K-nearest Neighbor, Support Vector Machine (SVM), Decision trees (Random Forest), neural networks etc.

Analysis/Model Evaluation: It is finally time for evaluation of the model. So, we then dive into the evaluation metrics. For typical classification, there are metrics such as accuracy, preicision, recall, f1, confusion matrix whereas a bit of stats is involved in regression as there are numbers : MSE (Mean Squared Error), MAE (Mean Absolute Error), R^2 (r-squared) . We do not use all of these metrics at once but use it as per the need of the outcome. All of these should be thought by the human trained while doing the EDA itself.

Serving the model : Put the model into production and see how it goes. This is when a ML model is really tested.

Retrain the model : See how the model performs after putting it into the production and visit the above steps again – retraining makes this entire process a feedback loop. 

