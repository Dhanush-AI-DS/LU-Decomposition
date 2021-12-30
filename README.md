# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:

```
/*
Program to find the L and U matrix.
Developed by:Dhanush.S 
RegisterNumber:21004324 

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*\
```
## Output:
![gitlogo](13.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.



(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Dhanush.S   
RegisterNumber:21004324 

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=([4, 5, 7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*\
```
## Output:
![gitlogo](12.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

