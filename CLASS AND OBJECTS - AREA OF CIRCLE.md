# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

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

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

from math import pi
class umbrella():
    def rain():
        r=int(input())
        return pi*(r**2)
        
print("Area of circle:",round(umbrella.rain(),2))

```

### OUTPUT

![image](https://github.com/user-attachments/assets/e4b6439e-2bb6-4451-81e6-84a9ca2d8212)

### RESULT

Thus, the Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain` has been executed and verified successfully.


