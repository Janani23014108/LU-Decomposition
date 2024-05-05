# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: J.JANANI
RegisterNumber: 212223230085

from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)


*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: J.JANANI
RegisterNumber: 212223230085

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
(i) To find the L and U matrix




![maths exp 5](https://github.com/Janani23014108/LU-Decomposition/assets/146822085/774e9e72-66cb-444c-88af-85e3f3fc28da)

(ii) To find the LU Decomposition of a matrix



![maths exp 5  2](https://github.com/Janani23014108/LU-Decomposition/assets/146822085/510554c6-a4da-4190-bb2e-33d0c48dacb8)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

