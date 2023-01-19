# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
	
## Program:
```
# Register No:22008563
# Developed By:Suji.G

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm = "{:.2f}".format(ans)
print(norm)




# 2-Norm of a Matrix

import numpy as np
rix=np.array(eval(input()))
res= np.linalg.norm(rix,2)
norm = "{:.2f}".format(res)
print(norm)



# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm = "{:.2f}".format(ans)
print(norm)



```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot from 2023-01-19 09-07-13](https://user-images.githubusercontent.com/119559822/213350399-a8e5c447-e769-41cb-bbf6-15c63fafe7a6.png)




### 2-Norm of a Matrix
<br>![Screenshot from 2023-01-19 09-07-49](https://user-images.githubusercontent.com/119559822/213350316-8e3c893a-857b-457e-bfb7-2a3c53747dd8.png)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot from 2023-01-19 09-08-14](https://user-images.githubusercontent.com/119559822/213350361-0b45d072-afd1-465b-b507-645d0ee6e3b2.png)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
