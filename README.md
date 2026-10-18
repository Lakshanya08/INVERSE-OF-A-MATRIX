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
<img width="357" height="428" alt="image" src="https://github.com/user-attachments/assets/3274173a-eafd-48d8-9c48-7b134d67b9b5" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

