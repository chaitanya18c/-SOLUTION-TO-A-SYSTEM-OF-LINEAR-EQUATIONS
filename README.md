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
#Developed by: Chaitanya P S
#RegisterNumber:212222230024
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
soln=np.linalg.solve(A,B)
print(soln)
```

## Output:
![image]![Screenshot 2023-04-03 112254](https://user-images.githubusercontent.com/119392724/229422913-73c1c7fe-431f-4627-895e-0f5680c36d49.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

