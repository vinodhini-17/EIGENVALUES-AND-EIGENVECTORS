# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import NumPy
### Step 2: 
Define the Matrix A
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
 Calculate Eigenvalues and Eigenvectors
### Step 4: 
Print the Results
## Program:
``````
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are" ,values,"and Eigen Vectors are",vectors)
``````
## Output:
![eigen](https://github.com/vinodhini-17/EIGENVALUES-AND-EIGENVECTORS/assets/145742741/4879df9b-71ce-4a84-b3e2-60cd38ab7d8d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
