# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Define matrix.
### Step 2: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 3: Print the eigenvalues and eigenvectors.


## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: javan rufus j
#RegisterNumber:24002549
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_values,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))
~~~

## Output:
![output](![Alt text](<Screenshot from 2024-12-26 14-42-13.png>))
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
