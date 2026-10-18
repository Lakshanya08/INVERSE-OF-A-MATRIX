# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy library.
### Step 2: 
Create the given matrix using np.array().
### Step 3: 
Use np.linalg.inv() to find the inverse of the matrix.
### Step 4: 
Store the inverse matrix in a variable named b.
### Step 5:
Print the inverse matrix using print(b).

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: LAKSHANYA.N
#RegisterNumber:212224230136
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1392" height="651" alt="image" src="https://github.com/user-attachments/assets/aec0185e-4ed2-4d19-b403-ca1c97b650e7" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

