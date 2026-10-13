# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the NumPy module to use the built-in functions for calculation
### Step 2: 
Create the given matrix using np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
#Program to find the rank of a matrix.

#Developed by: Kishore Kumar.P

#RegisterNumber:26002452

import os

os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[1, 2, 3], [3, 6, 9]])

C = np.linalg.matrix_rank(A)

print(C)

## Output:<img width="1291" height="901" alt="Screenshot 2026-10-13 201246" src="https://github.com/user-attachments/assets/7ac78f51-ad37-45de-a2c9-92f77cb6bc95" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

