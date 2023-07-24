# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## (i) To find the L and U matrix
## STEP 1:
import numpy module as np 
## STEP 2:
from scipy.linalg import lu to solve l and u matrix
## STEP 3:
get input array from the user and apply lu function to find l and u matrix
## STEP 4:
End of program

## (ii) To find the LU Decomposition of a matrix
## STEP 1:
import numpy module as np 
## STEP 2:
from scipy.linalg import lu_factor() and lu_solve() 
## STEP 3:
get input array from the user and apply lu_factor() and lu_solve() to find lu decomposition of the matrix
## STEP 4:
End of program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: YASHWINI M
RegisterNumber: 23004946
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: YASHWINI M
RegisterNumber: 23004946
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
```

## Output:
(i) To find the L and U matrix
![Alt text](<LU DECOMPOSITION.png>)

(ii) To find the LU Decomposition of a matriX
![Alt text](<LU MATRIX.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

