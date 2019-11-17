# Machine Learning Deployment using AWS SageMaker

The mini-projects and the project are pursued as a part of Machine Learning Engineer Nanodegree by Udacity. A great deal of code was developed by the Udacity team and in not my original work.

This repository contains code and associated files for deploying a plagiarism detector using AWS SageMaker.

## Table Of Contents

### Mini-Projects
* [IMDB Sentiment Analysis - XGBoost (Batch Transform)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Batch%20Transform).ipynb) is a notebook that leads you through the steps of constructing a model using XGBoost to perform sentiment analysis on the IMDB dataset.
* [IMDB Sentiment Analysis - XGBoost (Hyperparameter Tuning)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Hyperparameter%20Tuning).ipynb) is a notebook that leads through the steps of constructing a sentiment analysis model using XGBoost and using SageMaker's hyperparameter tuning functionality to test a number of different hyperparameters.
* [IMDB Sentiment Analysis - XGBoost (Updating a Model)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Updating%20a%20Model).ipynb) is a notebook that leads through the steps of constructing a sentiment analysis model using XGBoost and then exploring what happens if something changes in the underlying distribution. After exploring a change in data over time you will construct an updated model and then update a deployed endpoint so that it makes use of the new model.

### Project

[Sentiment Analysis Web App](https://github.com/udacity/sagemaker-deployment/tree/master/Project) is a completed notebook and collection of Python files. The result is a deployed RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint.
