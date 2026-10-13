# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy to module to use the build-in function for calculations 
### Step 2: initialize the given matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: stop the program

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by: Sanjay R
### RegisterNumber:26009894
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### B,C=np.linalg.eig(A)
### print("Eigen values are {} and Eigen Vectors are {}".format(B,C))

## Output:
<img width="1237" height="786" alt="{A2B2E437-CB05-4610-B85E-ECD25CA20FB7}" src="https://github.com/user-attachments/assets/4f984404-f898-48a1-9497-c217216e9f0f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
