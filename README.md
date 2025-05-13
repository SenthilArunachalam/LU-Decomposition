# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: End the program


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:P.Senthil Arunachalam
RegisterNumber: 212224240147
'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:P.Senthil Arunachalam
RegisterNumber:212224240147 
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![image](https://github.com/user-attachments/assets/f28301c1-2ba4-410a-8b2f-05f4b2005f80)

![image](https://github.com/user-attachments/assets/ee6f033c-d9a8-46ea-b834-1356d8df99eb)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

