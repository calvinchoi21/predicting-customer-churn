# Predicting Customer Churns with Classification Algorithms

![](/images/curves.jpg)

The purpose of the project was to utilize customer record data from a telco company to predict whether they would leave the company, or in other words churn. Six classification algorithms are tested and shortlisted for this task. The precision and recall trade-off for each model is also considered to simulate the real-life business decision made by an organization. 

- Dataset contains 3,333 records, each containing customer information. Target feature is either 'yes' or 'no', indicating whether that customer churned. 
- Due to heavy class imbalance of target feature, custom metric (based on f1-score of the minority class) is used to grade each model. 
- Six classifiers are initially tested using 5-fold cross-validation, and three are shortlisted based on score of custom metric. 
- Optimized shortlisted models using GridSearchCV to find the best models. 
- Tweaked decision threshold of each model to arrive at desirable precision/recall tradeoff. 
- Plotted PR curves to visualize and compare strength of final models.
- Code: [Link](https://github.com/calvinchoi21/predicting-customer-churn/blob/master/Classification_Customer_Churn.ipynb)

