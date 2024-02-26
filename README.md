# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the standard Libraries.

2.Set variables for assigning dataset values.

3.Import linear regression from sklearn.

4.Assign the points for representing in the graph.

5.Predict the regression for the marks by using the representation of the graph.

6.Compare the graphs and hence we obtained the linear regression for the given datas

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: MOHAMMED IMTHIYAS .M
RegisterNumber: 212222230083
```
*/

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
X=df.iloc[:,0:1]
Y=df.iloc[:,-1]
X
from sklearn.model_selection import train_test_split
X_train,X_test,Y_train,Y_test=train_test_split(X,Y,test_size=0.2,random_state=0)
from sklearn.linear_model import LinearRegression
lr=LinearRegression()
lr.fit(X_train,Y_train)
X_train
Y_train
lr.predict(X_test.iloc[0].values.reshape(1,1))
plt.scatter(df['X'],df['Y'])
plt.xlabel('X')
plt.ylabel('Y')
plt.plot(X_train,lr.predict(X_train),color='red')
m=lr.coef_
m[0]
b=lr.intercept_
b
```

## Output:


![307230658-a18699e6-a5ca-4980-94e5-4c869fc402c6](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/bbaf7215-a08f-4e31-9662-ce3862b245e6)




![307230923-96acf869-f98e-468d-930b-f0f1dc455930](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/60ad26eb-422f-46bc-98fe-26413617926e)

![307231019-1a683fab-aca5-4876-865f-9ed8ebe0e093](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/297a5f94-d584-4da7-93a5-8ac664993eec)



![307231087-8e998bb8-e7fb-4803-92f5-d2c309a44432](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/86161ba7-6cc2-41ee-b247-6aae7e162ecc)





![307231144-e3f494ae-8dd7-4bce-bab7-e1e79d90b8a9](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/0186f8da-f647-4e26-8884-9fdf428ba3cf)

![307231207-1f5a138b-2dfe-4bf9-bca0-a47e097cb832](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/94207828-da15-4bfb-bc12-3b8d2c31759b)


![307231252-9e41884a-0090-4164-9909-74e85e1e16e7](https://github.com/imthiyas19/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/120353416/10bf29e7-04dd-428e-8ce5-ee1ed4287ae1)









## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
