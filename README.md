# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
	1-norm:

1.Get the input matrix using np.array()
2.Compute column-wise absolute sum using np.sum(abs(A), axis=0)
3.Find the maximum value among the column sums → that is 1-norm
4.Print the norm value in two decimal places

2-norm:

1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

Infinity norm:

1.Get the input matrix using np.array()
2.Compute row-wise absolute sum using np.sum(abs(A), axis=1)
3.Find the maximum value among the row sums → that is infinity norm
4.Print the norm value in two decimal places
S
```
## Program:
```Python
# Register No:212225040075
# Developed By: Dhivakar B
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
<br>
<img width="1305" height="661" alt="image" src="https://github.com/user-attachments/assets/19e29e69-f3da-4f17-b4f4-306c8453e561" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1277" height="943" alt="image" src="https://github.com/user-attachments/assets/c03f285d-b399-4d46-8835-bd53b926961e" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1273" height="835" alt="image" src="https://github.com/user-attachments/assets/74b83863-f072-4316-8459-cc1d8bd4b39e" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
