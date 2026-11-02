# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the required libraries: NumPy, Matplotlib and Scikit-learn.
2. Create the dataset containing study hours and student marks.
3. Create a Simple Linear Regression model.
4. Train the model using the `fit()` function and predict marks using `predict()`.
5. Display the predicted marks and plot the regression line.

## Program:
```
/*
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression

# Input data
hours = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]).reshape(-1, 1)
marks = np.array([10, 20, 30, 40, 50, 60, 70, 80, 90, 100])

# Create Linear Regression model
model = LinearRegression()

# Train the model
model.fit(hours, marks)

# Predict marks
study_hours = [[7.5]]
predicted_marks = model.predict(study_hours)

print("Study Hours:", study_hours[0][0])
print("Predicted Marks:", predicted_marks[0])

# Plot graph
plt.scatter(hours, marks, color='blue', label='Actual Marks')
plt.plot(hours, model.predict(hours), color='red', label='Regression Line')

plt.xlabel("Study Hours")
plt.ylabel("Marks")
plt.title("Student Marks Prediction using Linear Regression")
plt.legend()
plt.show()
*/
```

## Output:
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/9c0f5178-09e3-4c49-a301-0627c451274e" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
