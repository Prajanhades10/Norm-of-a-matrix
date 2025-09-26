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
# Register No: 212224230201
# Developed By: PRAJAN.SS
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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

<img width="1300" height="959" alt="Screenshot 2025-09-26 111715" src="https://github.com/user-attachments/assets/89e0ea3e-f655-4b77-8b5b-0af1ddf0706a" />


### 2-Norm of a Matrix

<img width="1331" height="956" alt="Screenshot 2025-09-26 111729" src="https://github.com/user-attachments/assets/795df228-10a1-4f0f-9b99-e2cb61f871ca" />


### Infinity Norm of a Matrix

<img width="1429" height="938" alt="Screenshot 2025-09-26 111739" src="https://github.com/user-attachments/assets/cdd48ff9-da6a-43b2-9cef-2f4fd1a5cacd" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
