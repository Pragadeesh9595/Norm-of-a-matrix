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
# Register No: 25018154
# Developed By:pragadeesh.m

# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)


# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")


# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)



```
## Output:
### 1-Norm of a Matrix
<img width="1355" height="836" alt="Screenshot 2025-12-04 205333" src="https://github.com/user-attachments/assets/fc81928f-8b8d-4915-a498-52be235787a9" />


### 2-Norm of a Matrix
<img width="1181" height="769" alt="Screenshot 2025-12-04 205354" src="https://github.com/user-attachments/assets/e1f9fc81-8f98-491f-b115-d2e86da2671a" />

### Infinity Norm of a Matrix

<img width="1089" height="794" alt="Screenshot 2025-12-04 205417" src="https://github.com/user-attachments/assets/ac289963-6f36-4cbb-9f07-a670baa74fad" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
