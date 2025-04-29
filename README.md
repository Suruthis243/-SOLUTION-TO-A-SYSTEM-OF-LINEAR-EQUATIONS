# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: SURUTHI S
#RegisterNumber: 212224220114
import numpy as np
a=np.array([[1,-3], [3,1]])
b=np.array([0,10])
result=np.linalg.solve(a,b)
print(result)
```
## Output:
![Screenshot 2025-04-29 125724](https://github.com/user-attachments/assets/f748e536-1690-4986-8f2c-23af6f281663)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

