
# Python Basics  
This folder contains basic Python concepts, including variables, loops, functions, and object-oriented programming.

# Python 

 contains essential Python concepts with practical examples for each topic. It's designed for beginners who want to understand Python fundamentals through code examples.

## 1. Data Types
Python has several built-in data types used to store and manipulate different kinds of data.

| Type   | Description                                Example                        
|--------|-------------------------------------|--------------------------------
| `int`  | Integer numbers                     | `x = 10`                       
| `float`| Decimal numbers                     | `y = 10.5`                     
| `str`  | Strings (text)                      | `name = "Python"`              
| `bool` | Boolean values (True or False)      | `is_active = True`             
| `list` | List (mutable collection)           | `fruits = ["apple", "banana"]` 
| `tuple`| Tuple (immutable collection)        | `colors = ("red", "green")`    
| `dict` | Dictionary (key-value pairs)        | `person = {"name": "John", "age": 30}`

## 2. Variables
 Variables are used to store data in memory, which can be referenced and manipulated in the program.

### Example:

name = "dodo"
age = 25
height = 1.75
is_student = False
=============================================================================
## 3.Arithmetic Operators
 Python supports basic arithmetic operations that allow you to perform calculations.


 Operator                  	       Description	                    Example
    +	                            Addition	                     x + y
    -	                            Subtraction	                     x - y
    *	                            Multiplication                   x * y
    /	                            Division	                     x / y
    %	                            Modulo (remainder)	             x % y
    **	                            Exponentiation (power) 	         x ** y

 ## Example:
x = 10
y = 3

print(x + y)  # 13
print(x - y)  # 7
print(x * y)  # 30
print(x / y)  # 3.3333
print(x % y)  # 1
print(x ** y) # 1000
=======================================================
 # 4.Conditional Statements
  Conditional statements are used to make decisions in the program based on conditions.   
       
 ## Example:
age = 18

if age >= 18:
    print("Allowed")
else:
    print("Not allowed")
     
====================================================================

# 5.Loops---
 Loops allow you to repeat a block of code multiple times.

 ** For Loop ** 
## Example:

          for i in range(5):
    print(i)  # 0, 1, 2, 3, 4
        
** While Loop **
## Example
    x = 0
while x < 5:
    print(x)
    x += 1
    
============================================================
# 6.Functions:
 Functions are reusable blocks of code that perform a specific task and return a result.

## Example:
    def greet(name):
    return f"Hello, {name}!"

    print(greet("Alice"))
 
=========================================================

 # 7.Object-Oriented Programming (OOP)
 Python supports object-oriented programming, which involves creating classes and objects.

## Example:
    class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def introduce(self):
        return f"My name is {self.name} and I am {self.age} years old."

    p1 = Person("Alice", 25)
    print(p1.introduce())
===============================================================
 # 8.File Handling
 Python provides functions to work with files—read and write files.

 ## Writing to a File:
    with open("test.txt", "w") as file:
         file.write("Hello, World!")
         
         
 ## Reading from a File:
    with open("test.txt", "r") as file:
         content = file.read()
         print(content)
      
====================================================================


