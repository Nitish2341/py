# Exercise: Functions in python
1. Write a function called calculate_area that takes base and height as an input and returns and area of a triangle. Equation of an area of a triangle is,
```
area = (1/2)*base*height

def calculate_area(base,height):
      return (1/2)*base*height
```

2. Modify above function to take third parameter shape type. It can be either "triangle" or "rectangle". Based on shape type it will calculate area. Equation of rectangle's area is,
```
def calculate_area(base, height, shape="triangle"):
    if shape == "rectangle":
        return base * height
    else:
        return 0.5 * base * height

# Example
print(calculate_area(2, 5))               
print(calculate_area(2, 5, "rectangle")) 
print(calculate_area(2, 5, "triangle"))  

```
If no shape is supplied then it should take triangle as a default shape

3. Write a function called print_pattern that takes integer number as an argument and prints following pattern if input number is 3,
```
def print_pattern(value):
    for val in range(1,value+1):
        for el in range(1,val+1):
            print("*",end="")
        print()    
    return
#EXample
print_pattern(3)
print_pattern(4)
        

     
```
if input is 4 then it should print
```
*
**
***
****
```
Basically number of lines it prints is equal to that number. (Hint: you need to use two for loops)

[Solution](https://github.com/codebasics/py/blob/master/Basics/Exercise/10_functions/10_functions_exercise.py)
