# Implementation-of-Logistic-Regression-Using-Gradient-Descent

## AIM:
To write a program to implement the the Logistic Regression Using Gradient Descent.

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
Program to implement the the Logistic Regression Using Gradient Descent.
Developed by: HARI RAMESH
RegisterNumber:  25009620
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LogisticRegression
X = np.array([[30], [35], [40], [45], [50], [55], [60], [65]])
y = np.array([0, 0, 0, 0, 1, 1, 1, 1])   # 0 = Fail, 1 = Pass

model = LogisticRegression()
model.fit(X, y)

marks = [[48]]
result = model.predict(marks)
print("Prediction (0=Fail, 1=Pass):", result)

plt.scatter(X, y, color='red', label='Actual Data')

X_test = np.linspace(25, 70, 100).reshape(-1, 1)
plt.plot(X_test, model.predict_proba(X_test)[:,1], label='Prediction Curve')

plt.xlabel("Marks")
plt.ylabel("Probability of Pass")
plt.title("Logistic Regression: Pass / Fail Prediction")
plt.legend()
plt.show()*/
```

## Output:

<img width="816" height="542" alt="Screenshot 2026-01-28 205507" src="https://github.com/user-attachments/assets/a31f35ca-12bd-4ab9-81d5-e1cc5b8fa5d4" />
<img width="789" height="526" alt="Screenshot 2026-01-28 205453" src="https://github.com/user-attachments/assets/1688a64b-b10d-4868-9b83-5cfca0f1e654" />



## Result:
Thus the program to implement the the Logistic Regression Using Gradient Descent is written and verified using python programming.

