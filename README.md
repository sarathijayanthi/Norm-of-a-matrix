# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

1. 1-Norm of a Matrix:

Step 1: Get the input matrix from the user using eval(input()) and convert it into a NumPy array using np.array().
 
Step 2: Calculate the 1-norm (maximum column sum) of the matrix by calling np.linalg.norm(mat, 1).

Step 3: Format the resulting value to two decimal places using string formatting.

Step 4: Print the formatted 1-norm value.


2. 2-Norm of a Matrix:
 
Step 1: Get the input matrix from the user and convert it into a NumPy array using np.array().
 
Step 2: Calculate the 2-norm (Euclidean norm) of the matrix by calling np.linalg.norm(mat, 2).

Step 3: Format the resulting value to two decimal places.
 
Step 4: Print the calculated 2-norm.

3. Infinity Norm of a Matrix:
   
Step 1: Get the input matrix from the user and represent it as a NumPy array.

Step 2: Calculate the Infinity norm (maximum row sum) of the matrix by calling np.linalg.norm(mat, np.inf).

Step 3: Format the resulting value to two decimal places to ensure precision.

Step 4: Print the final Infinity norm result.


## Program:
```
# Register No:212225040249
# Developed By:MOHAMMED HANEEF M

# 1-Norm of a Matrix

##The 1-norm of a matrix (often called the maximum column sum norm) is calculated as the ## maximum sum of the absolute values of the elements in each column. 

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)


# 2-Norm of a Matrix

#The L2 norm (or Euclidean norm) of a vector measures the "length" or "magnitude" of the vector. Or it is the square root of sum of squares of all the elements

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)



# Infinity Norm of a Matrix

#The infinity norm of a matrix, often called the maximum row sum norm, is defined as the #maximum sum of the absolute values of the elements in each row.

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,np.inf)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix

<img width="1236" height="239" alt="image" src="https://github.com/user-attachments/assets/67d3ccab-84a2-4f7d-9b2b-412dbae1496e" />

<img width="1415" height="249" alt="image" src="https://github.com/user-attachments/assets/874d078e-5ea6-4987-af36-f6f280def4f4" />

### 2-Norm of a Matrix

<img width="886" height="219" alt="image" src="https://github.com/user-attachments/assets/eb49b3e7-da73-41e0-806e-db788c71867c" />

<img width="1402" height="222" alt="image" src="https://github.com/user-attachments/assets/860fd35a-db6f-4aa9-8ae7-f5f74fae2c6a" />


### Infinity Norm of a Matrix

<img width="1222" height="193" alt="image" src="https://github.com/user-attachments/assets/71adbe8a-6db4-492a-94dd-82c53ff00194" />

<img width="1417" height="220" alt="image" src="https://github.com/user-attachments/assets/bad2c66b-bf89-42cb-ab5d-f1d1f3208a96" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
