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
# Register No: 212225240058
# Developed By: Jeensfer Jo
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
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
<img width="652" height="557" alt="image" src="https://github.com/user-attachments/assets/7092fb0a-555f-48bd-8fbe-9a6c92185ca7" />


### 2-Norm of a Matrix
<img width="460" height="582" alt="image" src="https://github.com/user-attachments/assets/33079179-61cd-4a05-a02c-405a69c85dba" />


### Infinity Norm of a Matrix
<img width="537" height="480" alt="image" src="https://github.com/user-attachments/assets/f9b37f4d-c503-40a7-9670-7299074d6891" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
