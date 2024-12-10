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
# Register No:249000184
# Developed By: Elaiyavan K


# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matx="{:.2f}".format(ans)
print(norm_of_matx)


# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matx="{:.2f}".format(ans)
print(norm_of_matx)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matx="{:.2f}".format(ans)
print(norm_of_matx)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-10 210717](https://github.com/user-attachments/assets/22f58c51-c357-4fd1-b43f-24332b124523)

### 2-Norm of a Matrix
![Screenshot 2024-12-10 210730](https://github.com/user-attachments/assets/f09ed1a4-f510-4247-b8c4-a5f25cd1ba35)


### Infinity Norm of a Matrix

![Screenshot 2024-12-10 210744](https://github.com/user-attachments/assets/d5540f61-469c-4603-987e-5e499c5fbfce)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
