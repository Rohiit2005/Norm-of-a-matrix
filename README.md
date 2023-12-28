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
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Rohiit.A.S
RegisterNumber: 23010688
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




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
![exp7(1)](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849178/8f689c2f-acf7-4262-b70c-648deab1a304)


### 2-Norm of a Matrix
![exp7(2)](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849178/447ea7e7-cf2f-4402-bc12-8d07ecd8618e)


### Infinity Norm of a Matrix
![exp7(3)](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849178/4a4dff26-74b1-4794-bedd-24cfde326e87)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
