# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: PARAVEZHAA M
RegisterNumber: 212225220070

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

dataset = pd.read_csv("Salary.csv")

X = dataset.iloc[:, 1:2].values

y = dataset.iloc[:, 2].values

from sklearn.tree import DecisionTreeRegressor

regressor = DecisionTreeRegressor(random_state=0)

regressor.fit(X, y)
y_pred = regressor.predict([[6.5]])

print("Predicted Salary for Level 6.5:", y_pred)
X_grid = np.arange(min(X), max(X), 0.01)
X_grid = X_grid.reshape((len(X_grid), 1))

plt.scatter(X, y, color="red")
plt.plot(X_grid, regressor.predict(X_grid), color="blue")

plt.title("Decision Tree Regression")
plt.xlabel("Position Level")
plt.ylabel("Salary")

plt.show()

*/
```

## Output:
<img width="1491" height="705" alt="Screenshot 2026-03-12 103712" src="https://github.com/user-attachments/assets/d34e0b56-410f-422d-9fcc-15da272811aa" />


## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
