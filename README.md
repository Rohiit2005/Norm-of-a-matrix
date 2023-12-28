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
```Python
Program to find 2-norm of a matrix.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))A




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))






# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))






```
## Output:
### 1-Norm of a Matrix
![exp7(1)](https://github.com/Rohiit2005/Norm-of-a-matrix/assets/138849178/1570eed9-3549-4538-b344-9e1e9a686a7a)


### 2-Norm of a Matrix
![exp7(2)](https://github.com/Rohiit2005/Norm-of-a-matrix/assets/138849178/d7413060-80ed-43bd-b284-d69b4cdddf1a)


### Infinity Norm of a Matrix
![exp7(3)](https://github.com/Rohiit2005/Norm-of-a-matrix/assets/138849178/b6ac8e59-63da-4a00-b8ca-c6179c054aa2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
