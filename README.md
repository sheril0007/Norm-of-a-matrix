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
# Register No:212225230262
# Developed By:sheril.p
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="830" height="759" alt="image" src="https://github.com/user-attachments/assets/91fa0e43-9b8b-428e-bed2-8de8dd77a43a" />

### 2-Norm of a Matrix
<img width="817" height="848" alt="image" src="https://github.com/user-attachments/assets/04d5fef8-6152-472a-a46f-4a019e3db406" />


### Infinity Norm of a Matrix
<img width="789" height="824" alt="image" src="https://github.com/user-attachments/assets/68f43ed0-10aa-4311-a06d-663e7af8c650" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
