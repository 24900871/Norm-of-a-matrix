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
# Register No:212224230108
# Developed By: JOTHIMANI P 
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/ceb379e9-8c8f-4815-99d1-cdeee05b04a2)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/1235fe39-7955-4d14-b0cf-791cbfc991d8)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/da61d165-c0f2-4106-b8e8-0a72fa3a480a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
