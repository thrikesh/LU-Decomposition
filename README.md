# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:start
step 2:get an input from user
step 3: display the value 4.
step 4:stop

## Program:
(i) To find the L and U matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: thrikeswar p
RegisterNumber: 212222230162
*/

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
<br>![output](./ex5(mfa)a.png)
<br>![output](./ex5(mfa)b.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

