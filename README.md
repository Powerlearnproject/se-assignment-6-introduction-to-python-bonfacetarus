[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278823&assignment_repo_type=AssignmentRepo)
#SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, interpreted programming language known for its simplicity and readability. Some key features include:
Simple and Easy to Learn: Python syntax emphasizes readability and reduces the cost of program maintenance.
Interpreted and Interactive: Python programs are interpreted line by line, making debugging easy and allowing for an interactive mode.
Rich Standard Library: Python comes with a large standard library that supports many common programming tasks, such as string processing, file operations, and web services.
Cross-platform: Python runs on different platforms such as Windows, Linux, and macOS without any changes.
Wide Range of Applications: Python is used for web development (Django, Flask), scientific and numeric computing (NumPy, SciPy), artificial intelligence and machine learning (TensorFlow, PyTorch), and more.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

To install Python:
Windows: Download the installer from python.org and run it. Make sure to check "Add Python to PATH" during installation.
macOS: Python comes pre-installed on macOS, but you can install the latest version using Homebrew (brew install python) or from python.org.
Linux: Use your package manager (apt, yum, dnf, etc.) to install Python. For example, on Ubuntu: sudo apt-get install python3.
To verify:
Open a terminal or command prompt and type python --version or python3 --version to check the installed version.
To set up a virtual environment:
Install virtualenv using pip if not already installed: pip install virtualenv.
Create a new virtual environment: virtualenv myenv.
Activate the virtual environment:
Windows: myenv\Scripts\activate
macOS/Linux: source myenv/bin/activate

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

#Simple Python program to print "Hello, World!"
print("Hello, World!")
Syntax elements: print() is a built-in function that outputs text to the console. "Hello, World!" is a string literal enclosed in double quotes

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Basic data types in Python include:
int: integers (5, -10)
float: floating-point numbers (3.14, 2.718)
str: strings ("Hello", 'Python')
bool: boolean values (True, False)
list: ordered collection of items ([1, 2, 3])
tuple: ordered, immutable collection ((1, 2, 3))
dict: unordered key-value pairs ({'key': 'value'})

#Variables and data types
x = 5           # int
y = 3.14        # float
name = "Alice"  # str
is_valid = True # bool
#List example
numbers = [1, 2, 3]
#Dictionary example
person = {'name': 'John', 'age': 30}
#Accessing elements
print(numbers[0])     # Output: 1
print(person['name']) # Output: John


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

Conditional Statements (if-else):
code
#Example of if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")

Loops (for loop):
 code
#Example of for loop
numbers = [1, 2, 3, 4, 5]
for num in numbers:
    print(num)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions in Python:
Functions are blocks of code that executes a task
#Function to add two numbers
def add_numbers(a, b):
    return a + b
#Calling the function
result = add_numbers(9, 8)
print("Sum:", result)  # Output: Sum: 17

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists are ordered and mutable:
code
numbers = [1, 2, 3, 4, 5]
numbers.append(6)      # Add element
print(numbers)         # Output: [1, 2, 3, 4, 5, 6]
Dictionaries are unordered and indexed by keys:
code
person = {'name': 'Alice', 'age': 25}
print(person['name'])  # Output: Alice

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling is used to handle runtime errors gracefully.
code
try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules are Python files containing definitions and statements. Packages are directories of modules.
Example using math module:
code
import math
#Using math module
print(math.sqrt(16))    # Output: 4.0 (square root)  

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

#Reading from a file
with open('example.txt', 'r') as f:
    content = f.read()
    print(content)
#Writing to a file
data = ["Apple", "Banana", "Orange"]
with open('output.txt', 'w') as f:
    for item in data:
        f.write(item + '\n')  

Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


