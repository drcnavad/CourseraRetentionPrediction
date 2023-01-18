## Coursera Retention Prediction Competition

Coursera launched it's first ever data science competition on their platform where millions of students participated to predict user retention. 
Although, I achieved 71.18% score (top score: 76.55%) on their test dataset, the current python notebook is updated and may achieve higher score. I wasn't able to hypertune randomforest and xgboost due to low computational power.

If you go through my python notebook, I would love to hear your feedback and any guidance that will help me to improve. 


## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Challenge](#challenge)


#### Problem Statement
Coursera has a vested interest in understanding the likelihood of each individual learner to retain in their subscription so that resources can be allocated appropriately to support learners across the various stages of their learning journeys. In this challenge, we will be tackling the retention prediction problem on a very unique and interesting group of subscribers, Coursera learners!

#### Dataset
A real dataset (413955 rows × 37 columns) from Coursera to build a classification model that predicts whether a learner will or will not be subscribed to Coursera. The dataset is a sample of subscriptions that were initiated in 2021, all snapshotted at a particular date before the subscription was cancelled.

The dataset is proprietary to Coursera and I won't be uploading training and testing data csv file anywhere online. Please do not message me for the dataset.

#### Challenge
Imagine that you are a new data scientist at Coursera and you are tasked with building a model that can predict which existing specialization subscribers will continue their subscriptions for another month. 

To determine your final score, we will compare your predicted_probability predictions to the source of truth labels for the observations in test.csv and calculate the ROC AUC. We choose this metric because we not only want to be able to predict which subscriptions will be retained, but also want a well-calibrated likelihood score that can be used to target interventions and support most accurately.

## Contact
Created by [Chirag Navadia](https://www.linkedin.com/in/cnavadia/) - feel free to contact me on LinkedIn!
