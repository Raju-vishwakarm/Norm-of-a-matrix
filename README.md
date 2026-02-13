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
# Register No:212224240096
# Developed By : MOUNISH VAMSI KUMAR R
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
<img width="1793" height="1042" alt="Screenshot 2026-02-13 084557" src="https://github.com/user-attachments/assets/122b5f92-7548-4799-a1ab-6a73c46a609d" />


### 2-Norm of a Matrix
<img width="1621" height="1010" alt="Screenshot 2026-02-13 085341" src="https://github.com/user-attachments/assets/56c3cc36-1603-4240-bc03-118983fa322e" />


### Infinity Norm of a Matrix
<img width="1701" height="992" alt="Screenshot 2026-02-13 084715" src="https://github.com/user-attachments/assets/86e8d858-11c3-490b-aeee-86a082d14b8e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
