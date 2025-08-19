# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in js.array()
### Step 3: Using the js.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: JAYASURYA B
#RegisterNumber: 212224100026

import numpy as js
a = js.array([[2,2],[1,3]])
values,vectors = js.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:

<img width="1314" height="900" alt="Screenshot 2025-08-19 100320" src="https://github.com/user-attachments/assets/f3d519dd-f1cb-43b2-8c27-aa0652cb3294" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

