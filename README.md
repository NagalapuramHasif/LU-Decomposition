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
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by:NAGALAPURAM HASIF 
RegisterNumber: 212223100036
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: NAGALAPURAM HASIF
RegisterNumber: 212223100036
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/05618a77-fc85-41b0-908c-4d2bf880b3a0)
![image](https://github.com/user-attachments/assets/29818d23-1fc8-4e1c-9b49-ea0e3e495b79)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

