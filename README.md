EIGENVALUES-AND-EIGENVECTORS


Aim:

To write a python program to find the Eigenvalues and Eigenvectors.

Equipment’s required:


Hardware – PCs


Anaconda – Python 3.7 Installation / Moodle-Code Runner


Algorithm:


Step 1:

Import the NumPy library.

Step 2:

Read the matrix elements from the user and create a matrix using NumPy array.

Step 3:

Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:

Display the Eigenvalues and Eigenvectors of the matrix.

Program:

#Program to find the eigen values and eigen vectors.


#Developed by: P.PRIYADHARSHINI


#RegisterNumber:212225220076


import os

os.environ["OPENBLAS_NUM_THREADS"]="1"


import numpy as np


matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])


eig_values,eig_vector=np.linalg.eig(matrix)


print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vector}")


Output:

<img width="1918" height="1078" alt="Screenshot 2026-05-11 010951" src="https://github.com/user-attachments/assets/0e137ea5-35dc-4fef-881b-5077c14b4adc" />



Result:


Thus the Eigenvalue and Eigenvector is successfully solved using python program.
