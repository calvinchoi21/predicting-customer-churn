# Predicting Customer Churns with Classification Algorithms

## Overview
The purpose of this project is to predict whether a telco customer will leave the company, i.e. churn, by utilizing supervised learning in the form of classification. An example of why a company would employ this task is to identify exisiting customers that are likely to churn so that resources such as promotional material be allocated appropriately in an effort to retain them.

The data will be split into three set - 60% training, 20% validation, and 20% test. For this task, six classification algorthims are initially considered using cross-validation on the training set. Of those six, three are shortlisted for further modelling. For each of those models, the hyperparameters are tuned and the validation set is used to test the performance increase from the tuning. After a model is tuned, a precision and recall trade-off that is appropriate for the task is chosen for it. The final models are then tested on the validation set to compare performance. Finally, the models are tested once more on unseen data via the test set to determine the best performing model.

