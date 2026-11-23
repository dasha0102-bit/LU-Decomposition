# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

   

## Program:
(i) To find the L and U matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U) 

```
(ii) To find the LU Decomposition of a matrix
```

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

```

## Output:
### (i) To find the L and U matrix

<img width="1312" height="567" alt="image" src="https://github.com/user-attachments/assets/8b67eef3-b655-4c10-9978-134465464d62" />
 (ii) To find the LU Decomposition of a matrix

<img width="1337" height="332" alt="image" src="https://github.com/user-attachments/assets/6a8a6faa-0b58-4b8c-a71d-4c46e4c22e0d" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

