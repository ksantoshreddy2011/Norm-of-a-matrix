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
# Register No: 212225240137
# Developed By: SANTHOSH REDDY K
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array (eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

mat = np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix

<img width="1235" height="251" alt="Screenshot 2026-06-11 115946" src="https://github.com/user-attachments/assets/ddad2ba0-1df1-4772-ba64-d493042ee8f5" />


### 2-Norm of a Matrix

<img width="1226" height="279" alt="Screenshot 2026-06-11 120139" src="https://github.com/user-attachments/assets/5a03d22c-e15c-4016-aafe-981723b6092d" />


### Infinity Norm of a Matrix

<img width="1229" height="242" alt="Screenshot 2026-06-11 120235" src="https://github.com/user-attachments/assets/78dc9d3e-06a9-40ec-987f-8d57e253637c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
