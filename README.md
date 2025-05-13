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
# Register No:212224240040
# Developed By:Eesha Ranka
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
![image](https://github.com/user-attachments/assets/d2d96526-8f67-4d82-bfc4-67231803dd3d)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/330d6d4b-82af-43ba-ba13-adf4ccc264a8)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/cf4c4ca8-6ec7-4306-bd91-b4514d154755)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
