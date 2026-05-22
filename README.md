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
# Register No: 212225240026
# Developed By: Bhavankumar.P

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

<img width="1149" height="333" alt="Screenshot 2026-05-22 094402" src="https://github.com/user-attachments/assets/61566e52-f860-4d4a-a245-10fe3cb95f07" />





### 2-Norm of a Matrix

<img width="1030" height="364" alt="Screenshot 2026-05-22 094424" src="https://github.com/user-attachments/assets/666b3887-c0d5-46dd-b338-fc233199c896" />




### Infinity Norm of a Matrix
<img width="1201" height="329" alt="Screenshot 2026-05-22 094440" src="https://github.com/user-attachments/assets/aca0bb78-94f3-4c0f-bece-21d46c024b38" />





## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
