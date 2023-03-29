# Phase 3 Project SyriaTel-Churn-Predictive Modeling

[!awesome(https://idsb.tmgrup.com.tr/ly/uploads/images/2020/06/05/39374.jpg)

### Background
As important to Telecommunications companies as it is to earn new customers to their services, is the need to retain current customers and preventing them from going to competitors. The act of leaving customers or loss of customers are referred to in this industry as "Churn", from a business perspective. The business would like to understand exactly what factors or situations contribute to churning, and most importantly, post identification of those factors, define precises strategic initiatives to retain customers. This project, therefore aims to help the business first in identifying the attributes and factors that cause the churn, and in turn, building models that can help the business predict it, so that in fact strategic business initiatives can be outlined for solution.

### Business Understanding & Business Problem
As important to Telecommunications companies as it is to earn new customers to their services, is the need to retain current customers and preventing them from going to competitors. The act of leaving customers or loss of customers are referred to in this industry as "Churn", from a business perspective. The business would like to understand exactly what factors or situations contribute to churning, and most importantly, post identification of those factors, define precises strategic initiatives to retain customers. This project, therefore aims to help the business first in identifying the attributes and factors that cause the churn, and in turn, building models that can help the business predict it, so that in fact strategic business initiatives can be outlined for solution.


### The Data & Business Modeling Objectives
The database is a kaggle available dataset called "bigml_59c28831336c6604c800002a.csv", holding 3,333 values. 
The goal of this lab is to build the following with that data set: 
1) Identifying important attributes or features that are key in predicting customer churn
2) Building a model than can predict who will churn with a high level of accuracy

### Model Considerations Metrics (Recall)

Recall is an important metric in evaluating our model. Recall pertains to the rate at which the model makes correct predictions about customer churning. Aided by a C Matrix- our goal is to minimize false negatives. Failure to identify a customer who is about to churn is more costly from a business persepective, than wrongly classyging a non-churning customer. A good successful model therefore should have an 85% recall at the very least. Precision and accuracy are also metrics to have in mind.

### Conclusion & Recommendations

According to our analysis, the most important features in predicting churn are :

* The total number of minutes that the customer has done during the day
* The total number of evenining minutes
* The number of customer calls to customer service
* The total international minutes in international calls

The business recommendation to Syria Tel includes:
* For Syria tel, customer srvice is a key differentiatior. Syria tel should focus on training programs to enhance this features that mostly need to reduce the number of minutes spent by a customer on the phone. 
* Effective communication training customer service representatives is a key success factor. When a customer spends a higher number of minutes on the phone, this is an indication of higher churn. Also the call charge rates should be looked into. 
* A competition benchmark comparisson and a look into lowering the rates is also a factor in churning prevention.


## Summary
```
├── README.md                      <- The top-level README for reviewers of this project
├── index.ipynb                    <- Jupyter notebook. Overview, Business Problem, Data Understanding.Modelin
├── index.pdf                      <- PDF version of project presentation
├── data                            <- the database used 
└── BusinessPresentation.pdf        <- pdf of business presentation
└── Regression.png                  <- image sourced internally from notebook
```
![image](https://user-images.githubusercontent.com/102439898/228536267-8d3f8926-d49f-4557-add4-8b517261c6cd.png)

