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
# Register No:23004865
# Developed By:Lokhnath j
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)

## Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-11-26 115255](https://github.com/Lokhnath10/Norm-of-a-matrix/assets/138969918/04f3f7be-ce25-4e01-850b-33fb52411b3a)

### 2-Norm of a Matrix
![Screenshot 2023-11-26 115308](https://github.com/Lokhnath10/Norm-of-a-matrix/assets/138969918/4629150c-e011-4497-aeb5-50c32cce65b1)

### Infinity Norm of a Matrix
![Screenshot 2023-11-26 115318](https://github.com/Lokhnath10/Norm-of-a-matrix/assets/138969918/bb755637-b369-458b-b5ec-43cc6ac57e9a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
