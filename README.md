# EX-04: EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
Import Necessary Libraries
### Step 2: 
Define Matrix A
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the calculated eigenvalues and eigenvectors.

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by:KEERTHANA SARAVANAN
#RegisterNumber:23013398
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,Vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",Vectors)

```

## Output:

![image](https://github.com/KeerthanaaSaravanan/EX-04_MATH/assets/145742596/dc4c94b0-c731-4f52-bc13-2ed6afe6715e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
