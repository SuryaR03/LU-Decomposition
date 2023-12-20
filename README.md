# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built_in function for calculation
2. Prepare the lists fro each linear equations and assign in np.array()
3. Using the np.linalg.solve(),we can find the solutions
4. End of the program

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: SURYA R
RegisterNumber: 23013019
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix

'''Program to solve a matrix using LU decomposition.
Developed by: SURYA R
RegisterNumber: 23013019
'''

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

## Output:
![Screenshot 2023-12-20 105254](https://github.com/SuryaR03/LU-Decomposition/assets/147140237/b98d4926-7c53-4e43-8949-12f6ce81de74)
![Screenshot 2023-12-20 110224](https://github.com/SuryaR03/LU-Decomposition/assets/147140237/1de172dd-ce14-4632-9f6d-60af853c5e01)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

