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
# 1-Norm of a Matrix
```
python
# program to find the 1-Norm of a matrix display the result
# Developed by :BALASUDHAN P
# Register Number:212222240017

import numpy as np
mat= np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: BALASUDHAN P
RegisterNumber: 212222240017
'''
import numpy as np

mat = np.array  (eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
#program to find the Infinity of a matrix and display the result
#Developed by:BALASUDHAN P
#Register No:212222240017

import numpy as np 
 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-04 163610](https://github.com/BALASUDHAN18/Norm-of-a-matrix/assets/118807740/e2609f03-dcc3-496f-abd7-b82a33e164ae)


### 2-Norm of a Matrix
![Screenshot 2023-06-04 163435](https://github.com/BALASUDHAN18/Norm-of-a-matrix/assets/118807740/9b585fe6-a3dd-4948-89d6-ec8416842d12)


### Infinity Norm of a Matrix
![Screenshot 2023-06-04 163535 8](https://github.com/BALASUDHAN18/Norm-of-a-matrix/assets/118807740/3cf126ce-bf9e-4399-9c57-36a2a0e35b55)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
