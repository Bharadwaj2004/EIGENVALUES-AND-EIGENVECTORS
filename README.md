# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing the function , import numpy as np
### Step 2: 
taking input by using ,np.array([])
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
then print eigen value and vector by using format
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: B.venkata bharadwaj
#RegisterNumber:22003979
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![MODEL](/Screenshot%20(30).png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
