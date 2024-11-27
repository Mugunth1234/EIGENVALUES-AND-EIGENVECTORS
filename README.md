# EIGENVALUES-AND-EIGENVECTORS
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
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
import numpy as np
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors))
```

## Output:
![Screenshot 2024-11-27 220912](https://github.com/user-attachments/assets/0f816be0-9927-40ee-a9cb-31e2f52a05ee)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
