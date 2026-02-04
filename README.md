# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and read the matrix elements (number of rows and columns).
### Step 2: Convert the given matrix into a matrix object (using NumPy) and reduce it to its row echelon form.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Count the number of non-zero rows in the row echelon form of the matrix.
### Step 5: Display the count as the rank of the matrix and stop the program.
## Program:
```
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
x=np.linalg.matrix_rank(A)
print(x)
```
## Output:
<img width="1920" height="1080" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/1b3632aa-60d7-4def-a1e5-b532cc48a318" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

