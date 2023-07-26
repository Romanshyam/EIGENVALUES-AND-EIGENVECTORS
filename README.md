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
Prepare the lists from each linear equations and assign in np.array().
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program. 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:shyam kumar 
#RegisterNumber:23004557

import numpy as np
a=[2,2],[1,3]
b=np.array(a)
values,vectors=np.linalg.eig(b)
print('Eigen values are',values,'and Eigen Vectors are',vectors)
```

## Output:
![output](exp4.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
