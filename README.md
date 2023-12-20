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
# Register No:212223230105
# Developed By:K Kesava sai
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))



```
## Output:
### 1-Norm of a Matrix
![matex-7,1](https://github.com/Kesavasai20/Norm-of-a-matrix/assets/138849303/180ed846-5387-4695-a955-e92026ec989d)


### 2-Norm of a Matrix

![matex-7,2](https://github.com/Kesavasai20/Norm-of-a-matrix/assets/138849303/e2501b8c-ea55-4e05-b4f4-8e84d010a1ae)

### Infinity Norm of a Matrix

![mate-7,3](https://github.com/Kesavasai20/Norm-of-a-matrix/assets/138849303/a703327e-d9b5-4ddc-9fcb-0d59cbe03886)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
