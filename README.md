# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
```
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
```
## Algorithm:
```
 1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
## Program:
# Register No:Piritharaman R
# Developed By:23013537
# 1-Norm of a Matrix
```
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Piritharaman R
RegisterNumber: 23013537
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix:
```
import numpy as np
array1=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/ramanpiritha/Norm-of-a-matrix/assets/147084116/05020a28-88a3-4c72-a034-2a944d84461a)


### 2-Norm of a Matrix
![image](https://github.com/ramanpiritha/Norm-of-a-matrix/assets/147084116/704bd1de-ad88-4350-afee-e91f5a2ff186)


### Infinity Norm of a Matrix
![image](https://github.com/ramanpiritha/Norm-of-a-matrix/assets/147084116/6cec8587-2f7d-4dc3-b955-c62062cb9692)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
