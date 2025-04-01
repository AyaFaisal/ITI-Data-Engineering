# A Beginner's Guide to Python

## Introduction
Python is a powerful, easy-to-learn programming language created by Guido van Rossum in 1991. It’s widely used for web development, data science, automation, and more. This guide will help you start your Python journey with simple examples.

---

## 1. What is Python?
- Python is an open-source, high-level programming language.
- It’s known for its readable syntax and versatility.
- Great for beginners and professionals alike!

---

## 2. Installing Python on Linux
Most Linux distributions come with Python pre-installed. To check:
python3 --version
- If not installed (or you want a specific version):
  - **Ubuntu/Debian:**
    
    sudo apt update
    sudo apt install python3
   
  - **Fedora:**
    
    sudo dnf install python3
   
  - **Arch Linux:**
    
    sudo pacman -S python
   

---

## 3. Running Python
- **Interactive Mode:** Open the Terminal and type:
  
  python3
 
  You’ll see a prompt (`>>>`) where you can type Python code directly.

- **Script Mode:** Create a file with a `.py` extension:
  
  nano hello.py
 
  Write:
  ```python
  print("Hello, World!")
  
  Save (`Ctrl + O`, then `Ctrl + X`), then run:
 
  python3 hello.py
  
---

## 4. Basic Python Concepts
### Variables
- Store data like numbers or text:
 
  name = "Ali"
  age = 25
  print(name, "is", age, "years old")
  
### Data Types
- Numbers: int (e.g., 5), float (e.g., 3.14)
- Strings: str (e.g., "Hello")
- Lists: list (e.g., `[1, 2, 3]`)

### Conditionals
- Use if to make decisions:
 
  age = 18
  if age >= 18:
      print("You can vote!")
  else:
      print("Too young!")
  
### Loops
- Repeat tasks with for or while:
 
  for i in range(3):
      print("Count:", i)
  
---

## 5. Functions
- Define reusable code:
 
  def greet(name):
      return f"Hello, {name}!"
  
  print(greet("Sara"))  # Output: Hello, Sara!
  
---

## 6. Installing Packages
- Use pip (Python’s package manager):
 
  pip3 install package_name
  
- Example: Install requests to fetch web data:
 
  pip3 install requests
  
---

## 7. Simple Project Idea
Create a script to calculate the area of a rectangle:
width = float(input("Enter width: "))
height = float(input("Enter height: "))
area = width * height
print("Area:", area)


---

## 8. Why Learn Python?
- Easy syntax makes it beginner-friendly.
- Used in AI, machine learning, web apps, and more.
- Huge community and tons of libraries!

---

## 9. Resources
- [Python Official Docs](https://docs.python.org/3/)
- [Learn Python](https://www.learnpython.org/)
- YouTube: "Ezeroo" ,"Ahmad samy","Corey Schafer," "Tech With Tim" .