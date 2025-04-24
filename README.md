# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the necessary library, numpy, for matrix operations.
### Step 2:
Define the given matrix using the numpy.array() method.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors using the print() function.
## Program:
Program to find the eigen values and eigen vectors.<br>
Developed by  : AJAY S.<br>
RegisterNumber: 212224230010.<br>

import numpy as np<br>
a = np.array([[4,2],[2,4]])<br>
values,vectors = np.linalg.eig(a)<br>
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))<br>
## Output:
![Screenshot 2025-04-24 210230](https://github.com/user-attachments/assets/32a361ad-1068-4d6e-a506-f638a2067f6d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
