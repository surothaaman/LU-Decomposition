# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy package. 2.import scipy package and use linalg function from lu. 3.Using three(P,L,U) variables store lu(arr). 4.print L and U. 5.End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SUROTHAAMAN R
RegisterNumber: 23008504
import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SUROTHAAMAN R
RegisterNumber: 23008504
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
1
![Screenshot (31)](https://github.com/surothaaman/LU-Decomposition/assets/133313653/84fced94-5174-4a06-a040-02ac4850fd6c)
2
![Screenshot (32)](https://github.com/surothaaman/LU-Decomposition/assets/133313653/d94ecc11-b31b-4901-9c22-2cec2a862f27)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

