# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

## Aim:

To write a python program to find a solution to a system of linear equations.

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1: 

Import the numpy package

### Step 2: 

Get the input matrix

### Step 3: 

Find the system of linear equation

### Step 4: 

Print the output

## Program:

```python

#Program to find the solution for the given linear equations.
#Developed by:vaishnavi
#RegisterNumber:22009040
import numpy as np
A = np.array([[1,-3],[3,1]])
B = np.array([0,10])
sol = np.linalg.solve(A,B)
print(sol)

```

## Output:

![](./solution.png)

## Result:

Thus the solutions for the linear equations are successfully solved using python program