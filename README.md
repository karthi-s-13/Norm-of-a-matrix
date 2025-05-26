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
Python
# Register No: 212224230116
# Developed By: KARTHIKEYAN S
# 1-Norm of a Matrix
```import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```


# 2-Norm of a Matrix
```import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix
```import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-12-10 220334](https://github.com/user-attachments/assets/c9567871-3139-4110-bc73-c2bab736b688)

### 2-Norm of a Matrix
<br>![Screenshot 2024-12-10 220345](https://github.com/user-attachments/assets/57ba04f0-9aca-4037-a3ee-7c77865df7fb)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-12-10 220357](https://github.com/user-attachments/assets/2f371fe7-5062-46d9-9467-2a592b144cb7)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
