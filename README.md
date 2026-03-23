# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
Developed By : Mohit N
Register Number : 212225040255

# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
inf_matrix = np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))



```
## Output:
### 1-Norm of a Matrix
<img width="1309" height="820" alt="ex 7 -1" src="https://github.com/user-attachments/assets/3b43def1-7ba4-46d9-845f-2903d7f9a9c2" />


### 2-Norm of a Matrix
<img width="1042" height="844" alt="exp 7-2" src="https://github.com/user-attachments/assets/e568717c-ad1a-477a-a83e-737007501cf6" />


### Infinity Norm of a Matrix
<img width="1156" height="843" alt="exp 7-3" src="https://github.com/user-attachments/assets/f341076e-1ad1-4383-820e-f26d5a15c6e2" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
