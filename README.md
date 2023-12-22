# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the listfrom each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:aravind kumer ss
#RegisterNumber:23004721

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/aravindkumar23004721/EIGENVALUES-AND-EIGENVECTORS/assets/148962674/b97b4086-d322-4bf4-b567-443baab562d4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
