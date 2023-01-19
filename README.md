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
# Register No:22001908
# Developed By:B.Bejin
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
```Python
Program to find 2-norm of a matrix.
Developed by: B.Bejin
RegisterNumber:22001908 
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))
```



# Infinity Norm of a Matrix
```Python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118367518/213469334-b8154a98-8d54-4846-bfa2-a0b72eff1061.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118367518/213469427-9dd9a941-af34-4899-995c-b31c9eb2b517.png)

### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/118367518/213469507-b8a300ec-ee54-4594-b197-f1737bfcbee1.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
