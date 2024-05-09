# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable  
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```python
#Developed by: Kannan.S 
#RegisterNumber: 212223230098

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
#Developed by: Kannan.S
#RegisterNumber: 212223230098


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:
(i) To find the L and U matrix

![unit 2 ex 5(i)](https://github.com/Kannan-S-coder/LU-Decomposition/assets/147120710/6504129e-0b38-4f36-bf20-65e42595d0d5)

(ii) To find the LU Decomposition of a matrix

![unit 2 ex 5(ii)](https://github.com/Kannan-S-coder/LU-Decomposition/assets/147120710/baa685b2-6efa-44f7-92ac-c04b6bc9df3d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

