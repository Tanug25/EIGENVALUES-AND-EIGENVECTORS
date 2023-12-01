# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Start the program.
### Step 2: 
Prepare the lists from each inverse of a matrix and design in np.array().
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the Program.
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Tanushree A
#RegisterNumber:23004953
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
## Output:
![math op 4](https://github.com/Tanug25/EIGENVALUES-AND-EIGENVECTORS/assets/138849166/42818cc9-4f0c-48e5-bb75-4a6e076b17da)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
