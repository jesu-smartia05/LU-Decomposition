  # LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: JESU SMARTIA A
RegisterNumber: 23013932
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: JESU SMARTIA A
RegisterNumber: 23013932
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =np.array(eval(input()))
b =np.array(eval(input()))
lu,piv=lu_factor(A)
x =lu_solve((lu,piv),b)
print(x)
/*
```

## Output:
![lu decomposition]()

![Screenshot 2024-01-03 052538](https://github.com/jesu-smartia05/LU-Decomposition/assets/148514819/98e4e071-d534-4ad0-9519-ebb6ec5754f8)

![Screenshot 2024-01-03 052832](https://github.com/jesu-smartia05/LU-Decomposition/assets/148514819/853e2e1b-d929-4e2c-896e-c6b0f9ebcc1b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

