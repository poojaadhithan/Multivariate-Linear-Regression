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
import pandas as pd
from sklearn import linear_model

df = pd.read_csv("car.csv")

X = df[['Weight', 'Volume']]
y = df['CO2']

regr = linear_model.LinearRegression()
regr.fit(X, y)

print('Coefficients:', regr.coef_)
print('Intercept:', regr.intercept_)

predictedCO2 = regr.predict(pd.DataFrame([[3300, 1300]], columns=['Weight', 'Volume']))
print('Predicted CO2 for the corresponding weight and volume:', predictedCO2)

```
## Output:

### Insert your output
<img width="980" height="89" alt="image" src="https://github.com/user-attachments/assets/ad8469d7-e726-4e5f-9985-708f6820fd39" />

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
