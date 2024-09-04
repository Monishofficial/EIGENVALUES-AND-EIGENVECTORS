## DATE:
## EX 4 - EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MONISH N
#RegisterNumber: 212223240097

import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
B,C = np.linalg.eig(A)
print(f"Eigen values are {B} and Eigen Vectors are {C}")
```
## Output:
![Screenshot 2024-09-04 085530](https://github.com/user-attachments/assets/62a4b1fe-2789-47e9-96ce-fa86f970d4f5)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
