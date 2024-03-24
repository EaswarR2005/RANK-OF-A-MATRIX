# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program.
## Program:
#Program to find the rank of a matrix.

#Developed by: EASWAR R

#RegisterNumber:212223230053

import numpy as np

A=np.array([5,-3,-10],[2,2,-3],[-3,-1,5])

rank=np.linalg.matrix_rank(A)

print(rank)

## Output:
![Screenshot 2024-02-28 084340](https://github.com/EaswarR2005/RANK-OF-A-MATRIX/assets/146931525/2bee7c6d-1094-4d7c-bebb-c0052daf03c3)
![Screenshot 2024-03-24 212901](https://github.com/EaswarR2005/RANK-OF-A-MATRIX/assets/146931525/eac03863-c700-43c0-87ef-511fc2d50ff6)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

