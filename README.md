# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1. Start the program
### Step 2.Import the necessary libraries(numpy,scipy.linalg)
### Step 3.Define the matrix using numpy
### Step 4.Use lu(),lu_solve(),lu_factor() to get the solutions
### Step 5.End the program


## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: DEVASURYA M
#RegisterNumber: 25016815
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: DEVASURYA M
#RegisterNumber: 25016815
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="725" height="749" alt="Screenshot 2025-11-20 204806" src="https://github.com/user-attachments/assets/5e7f1b0d-f40e-4cac-b30e-84336d95188e" />
<img width="382" height="606" alt="Screenshot 2025-11-20 204827" src="https://github.com/user-attachments/assets/55791ebc-1abc-4f44-acf5-9eb996ef8ee4" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

