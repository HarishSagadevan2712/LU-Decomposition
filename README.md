# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## Program 1
1. Import numpy library
2. Import lu function from scipy library.
3. Solve LU decompostion using lu() function
4. print the value
## Program 2
1. Import numpy
2. From scipy.linalg import lu,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval
4. Print and solce LU decomposition using lu_solve() function

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: HARISH S
RegisterNumber: 212224110022
'''
import numpy as np
from scipy.linalg import lu
matrix=eval(input())
A = np.array(matrix)
P, L, U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: HARISH S
RegisterNumber: 212224110022

import numpy as np
from scipy.linalg import lu, lu_solve, lu_factor
A = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B = np.array([4, 5, 7])
lu_piv = lu_factor(A)
X = lu_solve(lu_piv, B)
print(X)
```

## Output:
![alt text](<Screenshot 2025-05-21 135034-1.png>)
![alt text](<Screenshot 2025-05-21 135043.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

