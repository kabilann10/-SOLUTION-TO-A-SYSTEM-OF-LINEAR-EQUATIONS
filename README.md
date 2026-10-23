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
'''import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=[-9,4,-1]
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
x=np.linalg.solve(A,B)
print(x)'''

## Output:

<img width="1417" height="756" alt="{ABA63B43-1552-4E24-AB03-FCCD314F48B9}" src="https://github.com/user-attachments/assets/c948e75c-b785-4220-b2fd-cdf6dcfc3759" />

<img width="1253" height="271" alt="{92B264E8-9001-40A5-B357-78A8CBAAE319}" src="https://github.com/user-attachments/assets/baa3f340-187d-46b3-8797-110cb60889ea" />




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

