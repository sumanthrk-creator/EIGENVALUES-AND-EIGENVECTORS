# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: sumanth RK
#RegisterNumber:26017294
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vecter=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vecter))

## Output:<img width="1457" height="554" alt="Screenshot 2026-10-23 082509" src="https://github.com/user-attachments/assets/32959d15-1bbb-4d8e-bc53-f8a7e1181113" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
