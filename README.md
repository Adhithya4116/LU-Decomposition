# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation 
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: adhithya perumal.d
RegisterNumber: 22008747
*/
```
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
Developed by: adhithya perumal.d
RegisterNumber: 22008747
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![dd](https://user-images.githubusercontent.com/118707079/215273460-9b70a787-767e-4ffd-ac64-1deae98fb1b1.png)
![ddd](https://user-images.githubusercontent.com/118707079/215273469-fe937ccd-0b09-4762-ab27-b71ff96c1091.png)
![Screenshot (4)](https://user-images.githubusercontent.com/118707079/215273505-51d29544-f51c-45f2-9785-8656ec0cf5cd.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

