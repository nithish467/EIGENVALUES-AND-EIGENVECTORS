# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
start with square matrix A
### Step 2:
solve the characteristic equation
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
eigen value and eigen vector calculation

## Program:
```
#name:NITHISH KUMAR S
#reference no:23013506
import numpy as np
A = np.array([[4,2],[2,4]])
eigenvalues,eigenvectors = np.linalg.eig(A)
print("Eigen values are",eigenvalues,"and","Eigen Vectors are",eigenvectors)

````


## Output:
![eigen value and eigen vector](https://github.com/nithish467/EIGENVALUES-AND-EIGENVECTORS/assets/150232274/4ff196c3-437f-46ad-b8c3-f34f0a2be2b8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
