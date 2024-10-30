# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists for the given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End of the program

## Program:
    
    #Developed by: JAYANI N
    #Register no : 24900024
    import numpy as np
    a=np.array([[2,2],[1,3]])
    eig_vals,eig_vectors=np.linalg.eig(a)
    print(f"Eigen values are {eig_vals} and Eigen Vectors are {eig_vectors}")

## Output:
![alt text](<Screenshot 2024-10-30 200850.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
