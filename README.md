# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module
### Step 2: prepare the list for matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HarrishVenkat
#RegisterNumber:23013973
import numpy as np
a=([[2,2],[1,3]])
eigenvalues,eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

```
## Output:
![eigenvalue](https://github.com/HarrishVenkat/EIGENVALUES-AND-EIGENVECTORS/assets/144979588/4fb33f0d-64fe-404b-827f-8ce046545266)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
