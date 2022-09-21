# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.solve(), we can find the solutions.
### Step 4: End the program
## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by:sharangini
#RegisterNumber:22003363
import numpy as np
A=np.array([[1,-3],[3,1]]) 
B=np.array([0,10]) 
C=np.linalg.solve(A,B) 
print(C) 
```
## Output:
![Screenshot from 2022-09-21 20-27-25](https://user-images.githubusercontent.com/113497104/191539506-9fd9b8c8-9944-40f7-9415-374c54b21f4f.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

