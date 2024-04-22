# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# DATE:02/03/2024
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
Developed by: KISHORE M
RegisterNumber: 2305002012
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution=np.linalg.solve(a,b)
print(solution)
```
## Output:
<img width="774" alt="Ss linear" src="https://github.com/kishore07062005/SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/156066116/275a7a16-75aa-4e04-9e63-286a7f898a02">
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

