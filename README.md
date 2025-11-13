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

# Register No:212224220126
# Developed By:Yuvan shankar M


# 1-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,1)
print("{:2f}".format(norm))


# 2-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm)) 



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm)) 
```

## Output:
### 1-Norm of a Matrix


<img width="1224" height="392" alt="image" src="https://github.com/user-attachments/assets/b0199ad5-6e4a-455e-a5f4-39f12fc60148" />


### 2-Norm of a Matrix


<img width="1228" height="439" alt="image" src="https://github.com/user-attachments/assets/13f5027f-617c-4080-af1f-f3bf7753b7bc" />


### Infinity Norm of a Matrix


<img width="1220" height="387" alt="image" src="https://github.com/user-attachments/assets/98053a53-31ba-4a3b-89b6-af200ce15067" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
