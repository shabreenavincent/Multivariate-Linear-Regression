# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Read the given dataset.
### Step2
Assign the attributes to X and Y respectively.
### Step3
Fit the X and Y features.
### Step4
Apply the Linear Regression Model to find the coefficient and intercept.
### Step5
Calculate the Prediction for CO2.
## Program:
```
register number:212222230141
student name:shabreena vincent

import pandas as pd
from sklearn import linear_model
df= pd.read_csv("/content/cars (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient",regr.coef_)
print("Intercept",regr.intercept_)
predictionCO2=regr.predict([[3300,1300]])
print("Prediction CO2 for the corresponding weight and volume",predictionCO2)






```
## Output:
![multi](https://github.com/shabreenavincent/Multivariate-Linear-Regression/assets/119475721/ba55d157-3ff1-4b3f-9059-1fe5ddeaead2)







## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
