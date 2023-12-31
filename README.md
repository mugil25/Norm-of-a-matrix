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
# Register No:212223230127
# Developed By:Mugil
# 1-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Mugil
RegisterNumber: 212223230127
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Mugil
RegisterNumber: 212223230127
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Mugil
RegisterNumber: 212223230127
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/mugil25/Norm-of-a-matrix/assets/148515771/e7fb28fc-f3ed-4cee-9a2e-8eb7f442fb9f)


### 2-Norm of a Matrix

![image](https://github.com/mugil25/Norm-of-a-matrix/assets/148515771/e57d4dfc-c480-4894-9f50-7727c5c7add9)

### Infinity Norm of a Matrix

![image](https://github.com/mugil25/Norm-of-a-matrix/assets/148515771/6f0ebd2b-49b9-428a-b8ed-1fe43827de05)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
