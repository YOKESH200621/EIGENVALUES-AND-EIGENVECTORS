# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import numpy as np
### Step 2: create a matrix using numpy
### Step 3: Using the np.linalg.eig(),  we get two results [First is eigenvalue and second is eigenvector] of the given matrix.
### Step 4: End the Program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YOKESH I
#RegisterNumber: 212224230313

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

a = np.array([[4, 2],
              [2, 4]])

values, vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))
```
## Output:
<img width="1872" height="1137" alt="image" src="https://github.com/user-attachments/assets/9b4d3e41-1d46-42df-89ca-721962796e69" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
