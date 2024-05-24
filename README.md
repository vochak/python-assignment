# python-assignment
question one
Python is an open-source, high-level, general-purpose programming language that has gained immense popularity due to its versatility, readability, and extensive ecosystem

question two
Download Python:
Visit the Python download page
Download the installer (usually an executable .exe file).
Run the Installer:
Double-click the downloaded installer file.
In the setup wizard, check the “Add Python 3.8 to PATH” option.
Click “Install Now” to begin the installation.
Wait for the installation to complete.
Verify the Installation:
Open the Run window (press Win + R).
Type cmd and press Enter to open the Command Prompt.
Type python and press Enter.
If you see Python’s version information, the installation was successful.
setting up the virtual environment
Navigate to your project directory.
Run:
virtualenv venv
(Replace venv with your preferred environment name.)
Activate the Virtual Environment:
On Windows:
venv\Scripts\activate

question three
# This program prints "Hello, World!"
print('Hello, World!')
The line starting with # is a comment.
The print('Hello, World!') line is the core of our program.
The print() function is a built-in Python function used to display output.

question four
Basic Data Types in Python:
Integers (int):
Represent whole numbers (positive, negative, or zero).
Examples: -5, 0, 42.
Floating-Point Numbers (float):
Represent decimal numbers with fractional parts.
Examples: 3.14, -0.5, 2.718.
Strings (str):
Represent sequences of characters (text).
Enclosed in single (') or double (") quotes.
Examples: 'Hello, World!', "Python".
Booleans (bool):
Represent truth values (True or False).
Used for logical operations.
Examples: True, False.


question five
Conditional Statements in Python:
1. If Statement:
The if statement executes a block of code only if a specified condition is met.
Syntax:
Python

if condition:
 


2. If-Else Statement:
The if-else statement provides an alternative block of code to execute when the condition is false.



3. Nested If-Else Statement:
You can have an if-else statement inside another if statement (nested).


4. If-Elif-Else Statement:
The if-elif-else statement allows you to handle multiple conditions.

Loops in Python:
1. For Loop:
The for loop iterates over sequences (lists, strings, tuples, etc.).

2. For Loop with range():
Use range() to create a sequence of numbers.
3. For Loop with else Clause:
The else block executes after the loop completes.
4. Nested For Loops:
You can have one for loop inside another.

question six
Functions in Python:
A function is a named sequence of statements that performs a specific task or set of tasks.
Functions help break down complex problems into smaller, more manageable pieces and promote code reuse.
def greet():
    print('Hello, World!')

# Call the function
greet()


question seven
A list is an ordered collection of elements.
Elements can be of any data type (integers, strings, floats, other lists, etc.).
Lists are created using square brackets [].

question eight
xception handling in Python allows you to gracefully handle errors and unexpected events that may occur during program execution. Instead of crashing the program, you can catch and manage these exceptions. Let’s explore how to use try, except, and finally blocks to handle errors:

question nine
A module is a file containing Python code (functions, classes, variables) that can be imported and used in other programs.
Modules allow you to organize code logically and reuse it across different parts of your application.

question ten
Reading from a File:
To read from a file in Python, follow these steps:

Open the File:
Use the open() function to open a file in read mode ('r').
Provide the file path as an argument.
Example:
Python

with open('my_file.txt', 'r') as file:
    content = file.read()
    print(content)

Open the File:
Use the open() function to open a file in write mode ('w').
Provide the file path as an argument.
Example:
Python

with open('output.txt', 'w') as file:
    file.write("Hello, World!\n")
    file.write("This is a new line.")


# Read and print the content of a file
with open('my_file.txt', 'r') as file:
    content = file.read()
    print(content)


# Write a list of strings to a file
my_list = ["Apple", "Banana", "Cherry"]

with open('fruits.txt', 'w') as file:
    for item in my_list:
        file.write(item + "\n")
reference
w3school.com
programiz.com
freecodecampblog















