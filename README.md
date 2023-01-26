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

Developed by : D.Vinitha Naidu
Register Number : 22001203

```
Program to find 1-norm of a matrix.

```
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,1)
print("{:.2f}".format(n))

```
Program to find 2-norm of a matrix.
```
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))

```
Program to find the infinity of a matrix and display the result in two decimal places.
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm = "{:.2f}".format(ans)
print(norm)
```

## Output:
![Output](/1.png)
```
```
![Output](/2.png)
```
```
![Output](/3.png)






## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
