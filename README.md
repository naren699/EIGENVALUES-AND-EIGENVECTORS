# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
## Developed by: NARENDHIRAN P
## RegisterNumber:24003040
    import numpy as np
    a=np.array([[4,2],[2,4]])
    value,vector=np.linalg.eig(a)
    print(f"Eigen values are {value} and Eigen Vectors are {vector}")

## Output:
![Screenshot 2024-11-21 224635](https://github.com/user-attachments/assets/bf09bd80-e658-4f7c-8a13-d962531e4760)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
