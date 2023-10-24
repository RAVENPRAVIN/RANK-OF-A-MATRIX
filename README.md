# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists from each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: PRAVIN KUMAR A.
#RegisterNumber:23007430
import numpy as np
A= np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![output](https://github.com/RAVENPRAVIN/RANK-OF-A-MATRIX/assets/146820534/3748bd98-bec3-4045-bd30-3af8c47bf581)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

