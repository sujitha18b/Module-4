# Exp.No:4A
## CLASS AND OBJECTS - AREA OF CIRCLE

### AIM  
To write Python Program to take the radius from the user and find the area of the circle using class name 'umbrella' and function name 'rain'

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.


### PROGRAM

import math      <br />
class umbrella: <br />
    def rain(r): <br />
        return math.pi*r*r <br />
r=int(input())   <br />
obj=umbrella   <br />
print("Area of circle:",round(obj.rain(r),2))


### OUTPUT
![Screenshot 2025-04-30 112410](https://github.com/user-attachments/assets/4d2211f6-f496-4752-8836-978c52b824b2)



### RESULT
Thus,the given python program is implemented and executed sucessfully.
