# EIGENVALUES-AND-EIGENVECTORS
# Date:06/04/2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing the NumPy library. 
### Step 2:
Define the given matrix A.
### Step 3: 
Use np.linalg.eig(A) to find the eigenvalues and eigenvectors.
### Step 4:
print and end the program.

## Question:

Write a program to find the eigenvalues and associated eigenvectors for the matrix [2,2],[1,3]

## Program:
```
program to find the solution for the given linear equation
Developed by:Gowtham S
RegisterNumber:2305002008
```
```python
import numpy as np
A=np.array([[2,2],[1,-3]])
values,vector=np.linalg.eig(A)
print("Eigenvalues are {} and Eigenvectors are {}".format(values,vector))
```

## Output:
![Screenshot 2024-04-07 174246](https://github.com/Ayvak16122005/EIGENVALUES-AND-EIGENVECTORS/assets/147690197/3c01f40d-35e5-4a90-9c83-258814f203a2)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
