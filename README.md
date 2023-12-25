# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. use the concept of LU decomposition
3. first find l and U matrix
4. Then find LU matrix
5. Stop the program

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Dhandeeswaran selvakumar
RegisterNumber: 23006838
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
Developed by: Dhandeeswaran selvakumar
RegisterNumber: 23006838
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
![output](https://github.com/AkilaMohan/LU-Decomposition/assets/147140237/32d3f707-7503-41c5-a054-6b908ffae54c)
![output1](https://github.com/AkilaMohan/LU-Decomposition/assets/147140237/6d863548-1871-44c3-9fd2-5b526bed99e2)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

