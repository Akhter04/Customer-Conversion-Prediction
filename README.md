# Customer-Conversion-Prediction
## Project statement

In the Customer Conversion Prediction project, machine learning models are used to predict whether a client will subscribe to an insurance policy. The project aims to help the insurance company identify the customers most likely to convert. This is to make sure that they can be targeted by phone calls and that the costs associated with telephonic marketing can be reduced as well. In order to train and evaluate the performance of the machine learning models, historical sales data will be used as the basis for training and evaluating them. The analysis of the model will be done to identify the crucial factors contributing to the conversion. The performance of the model will be evaluated using the AUROC metric.
## 1. Importing required libraries
## 2. Cleaning dataset

Cleaning missing value,duplicate,null values and data types
## 3.Exploratory data analysis
### Target variable analysis
![target](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/979c3993-8a81-4500-ad59-61ce8abfc2fc)

### Univariate analysis
![univariate](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/11a3d5cf-058e-4479-8613-e2a847818891)

### Bivariate analysis
![bivariate](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/887d98ab-ca09-4a7c-b2a1-90a70e9b9081)

### Correlation of data
![corelation](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/65d52587-9b4b-46ba-b029-da59ca51cc68)

## 4.Encoding data
## 5.Train test split
## 6.Scaling data
## 7.Models
Logistic regression,random forest,xg-boost

### AUROC Plot
![roc](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/a84e6aa7-e16c-434a-a4e8-b75ecab92954)

### Feature importance
![feature](https://github.com/Akhter04/Customer-Conversion-Prediction/assets/119933313/ccb28efe-a0b2-438c-bf0f-f97d3752da98)

### Conclusion
Random Forest outperformed all the other models with the highest AUROC score.
This implies that Random Forest is suitable to predict whether the client will subcribe to the insurance or not.
