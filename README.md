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
# Register No:25014908
# Developed By:K.Niwash
# 1-Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)
~~~








<img width="1221" height="742" alt="image" src="https://github.com/user-attachments/assets/1ae8382a-fd03-40e1-8cca-6750a99e3a1a" />




# 2-Norm of a Matrix
~~~
import numpy as np
a= np.array(eval(input()))
norm2= np.linalg.norm(a,2)
print(f"{norm2:.2f}")
~~~
<img width="1217" height="670" alt="image" src="https://github.com/user-attachments/assets/d7971514-1c0b-4588-85b1-c9256fae1039" />








# Infinity Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
norminfin=np.linalg.norm(a,np.inf)
print(f"{norminfin:.2f}")
~~~

<img width="1282" height="702" alt="image" src="https://github.com/user-attachments/assets/f212b6ab-281b-4973-8b8d-a9986d48df11" />




## Output:

### 1-Norm of a Matrix

<img width="1243" height="348" alt="image" src="https://github.com/user-attachments/assets/f72b262d-c205-4379-bc23-71c5c096e315" />

### 2-Norm of a Matrix

<img width="1232" height="422" alt="image" src="https://github.com/user-attachments/assets/4cf7603d-942a-4797-8f37-458caedb50c3" />


### Infinity Norm of a Matrix
<img width="1236" height="377" alt="image" src="https://github.com/user-attachments/assets/8e0f92f3-5f10-4e71-9fec-e98188820f1f" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
