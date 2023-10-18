# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import math module
### Step 2: 
Give the two co-ordinates for finding distance
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Use the in-built sqrt function to find the distance
### Step 5: 
Print the value of distance
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Kumarteja naramala
#RegisterNumber: 23003525
import math
x=[10,6]
y=[4,2]
d=math.sqrt(((x[0]-y[0])**2)+((x[1]-y[1])**2))
print("{:.2f}".format(d))
```
### OUTPUT:
![output](distance.png)
### RESULT:
Thus the program to find the distance between two points executed successfully.