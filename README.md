# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
Developed by: SAI GURU CHANDRAN G
Register number: 23014037

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("sai.csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO@ for the corresponding weight and volume",predictedCO2)





```
## Output:
![WhatsApp Image 2024-01-02 at 18 25 31_d323c27d](https://github.com/Saiguruchandran/Multivariate-Linear-Regression/assets/144870946/7c37fb69-aaf1-4471-89be-d88e1fe9d7d9)

### Insert your output
Coefficient: [0.00755095 0.00780526]
Intercept: 79.69471929115939
Predicted CO@ for the corresponding weight and volume [114.75968007]
## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
