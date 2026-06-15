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
...
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
x=np.linalg.solve(a,b)
print(x)
...
## Output:
<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/3049e2f9-51d0-4417-8297-6e1d9279482e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

