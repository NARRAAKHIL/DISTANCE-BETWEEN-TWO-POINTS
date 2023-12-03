# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: Using import math function,do the calculations.
### Step 2: Take the two coordinates as l1 and l2.
### Step 3: Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: using the print function, display the distance between the two points.
### Step 5: End the program.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Narra Akhil
#RegisterNumber:23003406
import math
def calculate_distance(x1,y1,x2,y2):
    distance = math.sqrt((x2-x1)**2 + (y2 -y1)**2)
    return round(distance, 2)
x1,y1 =4, 2
x2,y2 =10, 6
bridge_length = calculate_distance(x1,y1,x2,y2)
print(f"{bridge_length}")
```

### OUTPUT:
![image](https://github.com/NARRAAKHIL/DISTANCE-BETWEEN-TWO-POINTS/assets/144979843/d11b4bf2-cac7-40d1-a9e2-8effd893cdb3)


### RESULT:
Thus the distance of the two points is sucessfully executed and displayed.
