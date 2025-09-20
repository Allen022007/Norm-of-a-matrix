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
# Register No: 212224110004
# Developed By: W Allen Johnston Ozario
# 1-Norm of a Matrix

import numpy as np

arr = np.array(eval(input()))
one_norm = np.linalg.norm(arr,1)
print(one_norm)

# 2-Norm of a Matrix

import numpy as np

arr = np.array(eval(input()))
two_norm = np.linalg.norm(arr,2)
print(f"{two_norm:.2f}")

# Infinity Norm of a Matrix

import numpy as np

arr = np.array(eval(input()))
infinity = np.linalg.norm(arr,np.inf)
print(infinity)

```
## Output:
### 1-Norm of a Matrix
<img width="1119" height="329" alt="image" src="https://github.com/user-attachments/assets/d1384014-0c13-4ffd-b818-59371129ca49" />


### 2-Norm of a Matrix
<img width="966" height="384" alt="image" src="https://github.com/user-attachments/assets/5176d88f-94f8-4253-a586-c0b21d555e18" />


### Infinity Norm of a Matrix
<img width="867" height="345" alt="image" src="https://github.com/user-attachments/assets/14df0538-3dc0-4f7c-95cc-309f6d09e46c" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
