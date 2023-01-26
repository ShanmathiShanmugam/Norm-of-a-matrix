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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121243595/214869147-85e45d23-5f41-4895-9153-bba114a2c0e4.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121243595/214869259-6ea4a058-9fff-4348-b09e-19b0680b3658.png)

### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/121243595/214869372-82aa67e7-3e2a-45c3-bfdf-7f3af8f69fd9.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
