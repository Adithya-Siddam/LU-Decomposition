# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write a python program. 
2. Use numpy as np and open a special library named scipy.
3. Usinng eval data type get the input from the user.
4. Now complete the program and display the output and end the program.

## Program:
~~~
#Program to find L and U matrix using LU decomposition.
#Developed by: S Adithya Chowdary
#RegisterNumber: 21001700 
# To print L and U matrix

import numpy as np
from scipy.linalg import lu
A =eval (input())
P,L,U=lu(A)
print(L)
print(U)

## Program2:

#Program to solve a matrix using LU decomposition.
#Developed by: S Adithys Chowdary
#RegisterNumber: 21001700
# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = eval(input())
b = eval(input())
lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)

~~~

## Output:
![LU DECOMPOSITON](/IMAGES/decomposition.png)
![LU DECOMPOSITION](/IMAGES/decomposition2.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

