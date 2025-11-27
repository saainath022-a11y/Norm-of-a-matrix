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
1-Norm of a Matrix


```
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''developed by:SAAINATH B
register no: 25016015'''
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)
```




# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: SAAINATH B
RegisterNumber: 25016015
'''
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")
```


# Infinity Norm of a Matrix
```
'''developed by:SAAINATH B
register no:25016015
'''
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/7f614309-4453-4b9f-9dcf-da5c24e154fa" />
>

### 2-Norm of a Matrix
<br>
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/60c2b5d7-d542-4101-b8ab-3df9cf553676" />


### Infinity Norm of a Matrix
<br>
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/c4441808-00e8-4108-9b2f-0160b08bb883" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
