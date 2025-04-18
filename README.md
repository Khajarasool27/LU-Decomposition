# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

(i) To find the L and U matrix
## Algorithm

1. ### Step 1: Import NumPy and the LU decomposition function from SciPy.
2. ### Step 2: Step 2: Input the square matrix A.
3. ### Step 3: Step 3: Use `lu(A)` to get the L and U matrices (and permutation matrix P).
4. ### Step 4: Print the L and U matrices.

## Program:
```
'''Program to find L and U matrix using LU decomposition.
Developed by: BOYALAKUNTLA KHAJA RASOOL
RegisterNumber: 212224230040
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
## Algorithm

### Step 1: Import NumPy and LU-related functions from SciPy.
### Step 2: Input the coefficient matrix A and constant matrix B.
### Step 3: Perform LU decomposition using `lu_factor()` and solve using `lu_solve()`.
### Step 4: Display the solution matrix X.

## Program:

```
'''Program to solve a matrix using LU decomposition.
Developed by:BOYALAKUNTLA KHAJA RASOOL 
RegisterNumber: 212224230040
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
PV,LU=lu_factor(A)
result=lu_solve((PV,LU),B)
print(result)

```

## Output:
(i) To find the L and U matrix
![image](https://github.com/user-attachments/assets/90bb7a7e-40af-45df-aec1-9681c78364aa)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/5058cc00-2a69-41d7-bd54-f1958a930315)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

