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
# Register No:212223100038
# Developed By:N.neethiventhan 
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by:N.neethiventhan
RegisterNumber:212223100038 
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))





# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Neethiventhan123/Norm-of-a-matrix/assets/148514848/7618b742-7b22-4c89-9259-cf86a416091f)


### 2-Norm of a Matrix
![image](https://github.com/Neethiventhan123/Norm-of-a-matrix/assets/148514848/aab930ea-0ab2-4379-810c-01a7b68feca8)



### Infinity Norm of a Matrix
![image](https://github.com/Neethiventhan123/Norm-of-a-matrix/assets/148514848/076b3830-7e21-4bb8-9f44-204686379663)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
