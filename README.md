# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
print using .format model
### Step 5: 
print the coding
### PROGRAM:
~~~
#Program to find the distance between two points.
#Developed by: R.SOMEASVAR
#RegisterNumber:21500795
import numpy as np
l1=[10,6]
l2=[4,2]
distance=np.sqrt(((l1[0]-l2[0])**2)+((l1[1]-l2[1])**2))
print("{:.2f}".format(distance))
~~~
  


### OUTPUT:
![output](/distance.png)


### RESULT:
Distance between two point is calculated using python.
