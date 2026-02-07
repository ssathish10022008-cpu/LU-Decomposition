# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:

<img width="1919" height="1077" alt="Screenshot 2026-02-07 082546" src="https://github.com/user-attachments/assets/d8c0278f-dd3e-4ad9-ae90-d28e6313ba5c" />
<img width="1919" height="1073" alt="Screenshot 2026-02-07 082512" src="https://github.com/user-attachments/assets/7a65dd6a-a03c-457c-b54a-7f9deeb83a89" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

