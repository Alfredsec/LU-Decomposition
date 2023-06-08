# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the input matrix from user
2. write a program to find the L and U matri
3. using the L and U matrix slove the matrix
4. display the output

## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: Alfred A B
RegisterNumber: 212222110002
'''

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: Alfred A B 
RegisterNumber: 212222110002
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array(eval(input()))
B=np.array(eval(input()))
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
(i) To find the L and U matrix

![Screenshot 2023-06-08 120833](https://github.com/Alfredsec/LU-Decomposition/assets/120621608/45ce1e36-da8a-45f1-954c-aafc030130dc)

(ii) To find the LU Decomposition of a matrix

![Screenshot 2023-06-08 120854](https://github.com/Alfredsec/LU-Decomposition/assets/120621608/b52c6f7d-afb4-43d9-a8bf-9dfa87bcf031)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

