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

### ![Concrete composition elements vs Concrete Strength](/Images/pic1.png)        


### Feature Importance

The features that influence the prediction of Concrete Strength are:
* water/cement ratio
* age_3
* age_7
* slag
* superplastic

### Choosing the Best Regression Model
![Model Comparison Chart](/Images/df.png)

### Business Understanding and Inference:
 
Random Forest Regressor is identified to be the best Model in this scenario (High Test Accuracy Score and low RMSE) . Cross Validation is applied on this model to obtain the average accuracy of the model in Production, and hyperparameter tuning is done to extract the extra performance from the Model. The final Tuned Random Forest Regressor has an Accuracy Score of 90.1% and RMSE of 5.16
