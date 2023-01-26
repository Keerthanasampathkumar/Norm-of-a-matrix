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
```python
# Register No: KEERTHANA S
# Developed By: 22009006

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix
![pic 1](https://user-images.githubusercontent.com/119477890/214756479-3e6ae365-203d-4947-a419-d170a91599e6.png)



### 2-Norm of a Matrix
![pic 2](https://user-images.githubusercontent.com/119477890/214756464-6016a403-3576-4513-954d-46fdb3e2723e.png)



### Infinity Norm of a Matrix
![pic 3](https://user-images.githubusercontent.com/119477890/214756431-84fc2d2c-623d-412d-b988-75bd9c8ab2f6.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
