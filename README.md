# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy as np 
2. from scipy import lu
3. get the input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: pavithra k
RegisterNumber: 212224240112
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: pavithra k
RegisterNumber: 212224240112
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

```

## Output:
![Screenshot 2025-03-21 143033](https://github.com/user-attachments/assets/7bf78c62-6a40-441f-9f8c-e114d9ba219b)
![Screenshot 2025-03-21 143042](https://github.com/user-attachments/assets/379fce0d-0b25-4644-a2a6-ed67933eb738)
![Screenshot 2025-03-21 143204](https://github.com/user-attachments/assets/b3686e39-33a5-4508-9a2d-702055d4124a)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

