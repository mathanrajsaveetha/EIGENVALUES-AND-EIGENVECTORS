# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: using array function change the equation into a matrix  
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mathan Raj E
#RegisterNumber:22008971
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
value,vector=np.linalg.eig(a)
print(f'Eigen values are {value} and Eigen Vectors are {vector}')
```
## Output:
![output](eigenoutput.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
