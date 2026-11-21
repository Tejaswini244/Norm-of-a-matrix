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
# Register No:R.TEJASWINI
# Developed By:212224230218

# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np  
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)  
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

<img width="856" height="960" alt="image" src="https://github.com/user-attachments/assets/9e85b8f8-4612-469f-8f49-b81746d1fd36" />


### 2-Norm of a Matrix

<img width="817" height="970" alt="image" src="https://github.com/user-attachments/assets/f31424f0-5c4a-4cb0-bc68-0f99fea9e2ad" />


### Infinity Norm of a Matrix

<img width="757" height="957" alt="image" src="https://github.com/user-attachments/assets/fb90fed3-f9fa-4e00-8170-3b4a3c92be2d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
