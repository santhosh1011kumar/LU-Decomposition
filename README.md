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

Program to find the L and U matrix.
Developed by: Santhosh kumar A
RegisterNumber: 212224230250

import numpy as np 
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## Output:
<img width="1165" height="948" alt="image" src="https://github.com/user-attachments/assets/1ddadfa2-90b6-4c80-b8e6-5f0eaff0c514" />

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Santhosh Kumar A
RegisterNumber: 212224230250

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:

<img width="1025" height="770" alt="image" src="https://github.com/user-attachments/assets/59cdf602-5028-49bb-9ac9-44b9e0666f49" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

