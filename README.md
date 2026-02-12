# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import NumPy and create matrix A.
### Step 2:  Find eigenvalues and eigenvectors of A.
### Step 3: Store them in variables.
### Step 4: Print the result


## Program:
```
import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vector=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vector} ")
```

## Output:
<img width="1249" height="763" alt="Screenshot 2026-02-12 162130" src="https://github.com/user-attachments/assets/f503c6dd-18d0-4653-b1f4-c76cb2197308" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
