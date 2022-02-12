# Inverse-of-matrix

## AIM:
To find a Inverse-of-matrix

## ALGORITHM:
### Step 1:
import numpy as np
### Step 2:
Get the input in integer
### Step 3:
Append the list using for loop
### Step 4:
For finding inverse we give inverse =np.linalg.inv
### Step 5: 
now print(inverse)


## PROGRAM:
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range (n1):
    for j in range (n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)  
    l1=[]
print(l2)
Matrix=np.array(l2)
inverse=np.linalg.inv(Matrix)
print(inverse)

## OUTPUT:
![output](.//inverse.png)

## RESULT:
Thus the inverse of matrix is implemented using python programming.
