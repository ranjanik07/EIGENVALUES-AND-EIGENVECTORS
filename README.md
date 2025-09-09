# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define the square matrix A.
### Step 2: Use numpy.linalg.eig(A) to compute eigenvalues and eigenvectors.
### Step 3: Store the eigenvalues in one variable and eigenvectors in another
### Step 4: Display the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RANJANI K
#RegisterNumber: 212224230220
```
```
import numpy as np
A=[4,2],[2,4]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1231" height="293" alt="Screenshot 2025-09-08 094345" src="https://github.com/user-attachments/assets/0abf81a1-2da4-4110-849f-f8d4d5d6781a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
