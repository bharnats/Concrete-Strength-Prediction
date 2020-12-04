# Concrete-Strength-Prediction
## Data Description:
The dataset contains data on 1030 different composition mix and other features that determine the Concrete strength. The data include Concrete mix,Age and Concrete strength (Target Variable)
## Domain
Civil Engineering and Construction
## Objective:
This is a Regression problem, and is used to predict the Concrete Compressive Strength, based on the historical data
## Packages Used
* Pandas
* Numpy
* Matplotlib/Seaborn
* sklearn
## Exploratory Data Analysis

### ![ Vs. ](/Images/pic1.png)        ![ Vs.](/Images/pic2.png)
### ![](/Images/pic3.png)                              ![](/Images/pic4.png)

### Feature Importance

The features that influence the prediction of class 1 for the Target Variable (The customer will accept Personal Loan) are:
* 
* Fa
* F

The features that influence the prediction of class 0 for the Target variable (The customer will NOT accept Personal Loan) are:
* Educ
* Family_2
* Online

Mortgage, Age, Experience, Income and CreditCard DO NOT have much influence on the 'Loan Status'
 
### Business Understanding and Inference:
 
The ROC_AUC score is high, 0.905, Also the Recall score is high here 0.991 . So, we can say that this Logit Model is performing well in distinguishing positives from negative classes with less False Negatives.
