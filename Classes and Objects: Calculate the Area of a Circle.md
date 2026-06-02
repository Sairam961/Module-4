# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self,radius):
        area=math.pi * radius ** 2
        return area
r=float(input("Enter the radius: "))
circle_obj=cse()
print("Area =",circle_obj.mech(r))
```
## Output
<img width="1612" height="517" alt="image" src="https://github.com/user-attachments/assets/a07cac6a-ad3d-40e5-a1ec-22d9f3aa7a05" />

## Result
Thus the program has been successfully executed
