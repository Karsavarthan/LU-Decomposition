# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that
variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: karsavarthan r r
RegisterNumber: 23003628
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: karsavarthan r r
RegisterNumber: 23003628
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)


```

## Output:
![Screenshot 2024-01-04 151857](https://github.com/Karsavarthan/LU-Decomposition/assets/139841970/f60528b7-df68-45c1-86f8-e591ab05c82f)
![Screenshot 2024-01-04 151908](https://github.com/Karsavarthan/LU-Decomposition/assets/139841970/25805cab-5056-4d3f-a480-6f9af92674b4)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

