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
```
# 1-Norm of a Matrix
'''Developed by DHILSANRAJ S
Register no : 212225230058'''
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(round(result,2))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: DHILSANRAJ S
RegisterNumber: 212225230058
'''
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np

# Type your code here
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")



# Infinity Norm of a Matrix
#Developed by DHILSANRAJ S
#Register Number : 212225230058
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")


```
## Output:
### 1-Norm of a Matrix
<img width="1734" height="841" alt="Screenshot 2026-08-27 220601" src="https://github.com/user-attachments/assets/28c0db89-7e58-44a3-801c-05b322c5ea5e" />
### 2-Norm of a Matrix
<img width="1305" height="759" alt="Screenshot 2026-08-27 220619" src="https://github.com/user-attachments/assets/6c9faf65-ca21-4757-8a93-f3a74e5eead7" />
### Infinity Norm of a Matrix
<img width="1343" height="783" alt="Screenshot 2026-08-27 220649" src="https://github.com/user-attachments/assets/b5fe62c0-f6eb-4175-bd7c-540239d726aa" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.




