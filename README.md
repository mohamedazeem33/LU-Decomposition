# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:
Import the numpy module to use the built-in functions for calculation
step 2:
Prepare the lists from each linear equations and assign in np.array()
step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the
given matrix.
step 4:
End the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: MOHAMED AZEEM N
RegisterNumber: 22007405

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: MOHAMED AZEEM N
RegisterNumber: 22007405
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot (76)](https://user-images.githubusercontent.com/121040764/213394962-e24418f2-5844-4e2e-b35f-25e31c77b0a7.png)
![Screenshot (77)](https://user-images.githubusercontent.com/121040764/213394980-53592fa4-117b-42bf-b748-6fd16a255183.png)



## Result:
the LU Decomposition is successfully solved using python program

