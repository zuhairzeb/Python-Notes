---
cover: >-
  https://images.unsplash.com/photo-1660616246653-e2c57d1077b9?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw2fHxweXRob24lMjBwcm9ncmFtbWluZ3xlbnwwfHx8fDE3MjU2OTQ1NzF8MA&ixlib=rb-4.0.3&q=85
coverY: 142
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Python

## What is Python?

> Python is dynamically type. General purpose programming language that supports object-oriented programming approach as well as functional programming approach.

### Example

```python
print("Hello world")
```

### Why do we use Python?

***

Python is commonly used for:

* Web Development: Creating websites and web applications.
* Software Development: Building software applications and systems.
* Task Automation: Automating repetitive tasks to increase efficiency.
* Data Analysis and Visualization: Analyzing and visualizing data to derive insights.

Python's simplicity and ease of learning have made it popular among non-programmers, including accountants and scientists, who use it for various everyday tasks, such as organizing finances and analyzing data.

## History of Python:

Python was developed by Guido van Rossum in the late 1980s and early 1990s at the National Research Institute for Mathematics and Computer Science (CWI) in the Netherlands. Python draws inspiration from several languages, including ABC, Modula-3, C, C++, Algol-68, Smalltalk, and Unix shell scripting languages. These influences helped shape Python's design and features. Python is indeed copyrighted, but it is not distributed under the GNU General Public License (GPL). Instead, Python is available under the Python Software Foundation License, which is a permissive open-source license. The name "Python" is inspired by the British comedy series Monty Python's Flying Circus. It was chosen by Van Rossum, who was a fan of the show.Guido van Rossum was initially given the title Benevolent Dictator For Life (BDFL) by the Python community. In 2018, Van Rossum stepped down from this role. The development and distribution of Python are now overseen by the Python Software Foundation (PSF), a non-profit organization.

## Who Invented Python?

Python was invented by Guido van Rossum, a Dutch programmer, in the late 1980s. The first version of Python (0.9.0) was released in 1991.

<figure><img src=".gitbook/assets/guido.jpg" alt=""><figcaption><p>Guido van Rossum</p></figcaption></figure>

## Installing Python on Windows

> Download Python:

* Go to the [official Python website](https://www.python.org/downloads/).
* Click on the "Download Python" button for the latest version. The website will automatically detect your operating system.

Run the Installer:

* Locate the downloaded installer file (usually in your Downloads folder) and double-click it to run.
* Make sure to check the box that says "Add Python to PATH". This step is crucial for running Python from the command line.
* Click on "Install Now" to start the installation.

Verify Installation:

* Open the Command Prompt (you can search for `cmd` it in the Start menu).
* Type `python --version` and press Enter. You should see the version of Python you installed.
* You can also type `python` to enter the Python interpreter.

### Installing Python on macOS

> Download Python:

* Visit the [official Python website](https://www.python.org/downloads/).
* Click on the "Download Python" button for the latest version for macOS.

Run the Installer:

* Open the downloaded `.pkg` file and follow the instructions in the installer. This will guide you through the installation process.

Verify Installation:

* Open the Terminal (you can find it in Applications > Utilities).
* Type `python3 --version` and press Enter. You should see the version of Python you installed.
* You can also type `python3` to enter the Python interpreter.

### Installing Python on Linux

> Update Package List:

* Open the Terminal.
* Run `sudo apt update` to update your package list (for Debian-based distributions like Ubuntu).

Install Python:

* Run `sudo apt install` python3 to install Python 3.
* For additional tools and libraries, you can install python3-pip and `python3-venv` as well.

Verify Installation:

* In the Terminal, type `python3 --version` and press Enter. You should see the version of Python installed.
* You can also type `python3` to enter the Python interpreter.

### Setting Up a Virtual Environment (Optional but Recommended)

Create a Virtual Environment:

* Open the Command Prompt or Terminal.
* Navigate to the directory where you want to create your project.
* Run `python -m venv myenv` (replace `myenv` with your preferred environment name).

Activate the Virtual Environment:

* Windows: Run `myenv\Scripts\activate.`
* macOS/Linux: Run source `myenv/bin/activate.`

Deactivate the Virtual Environment:

* Simply run `deactivate` when you want to exit the virtual environment.

## Getting Started

## What is Syntax?

Syntax refers to the set of rules that define the structure of a programming language. It dictates how the symbols, keywords, and operators of a language are arranged to form valid code. In simpler terms, syntax is the grammar of a programming language, guiding how you should write your code so that it can be correctly understood and executed by a computer.

#### Example

#### Correct Syntax:

```python
print("Hello, world!")
```

This line of code follows Python's syntax rules for calling the `print()` function with a string argument.

#### Incorrect Syntax:

```python
print "Hello, world!"
```

This line is incorrect in Python 3 because the `print` function requires parentheses around the argument. If you run this, Python will give you a syntax error.

### Comments

Comments in programming are non-executable lines of text that you add to your code to explain what the code does, make notes, or temporarily disable code during debugging. They are ignored by the compiler or interpreter, so they don't affect the execution of the program.&#x20;

Comments are useful for:

* Documenting Code: Explaining the purpose of a function, block of code, or complex logic.
* Collaboration: Helping other developers understand your code.
* Debugging: Temporarily disabling parts of code to test and troubleshoot.

#### Types of Comments

#### 1. Single-Line Comments:

* Typically used for short explanations or notes.
* In most programming languages, single-line comments start with specific characters.

```python
# This is a single-line comment
print("Hello, world!")  # This comment explains the print statement
```

#### 2. Multi-Line Comments:

* Used for longer explanations that span multiple lines.
* The syntax varies depending on the language.

Python Example: (Note: Python doesn't have traditional multi-line comments, but you can use multi-line strings as a workaround.)

```python
"""
This is a multi-line comment.
It can span multiple lines.
"""
print("Hello, world!")

```

### Variables

A Python variable is a reserved memory location to store values.

```python
x = 5
y = "10"
print(x)
print(y)
```

#### Types of Variables

> Integers (`int`):

* These are whole numbers without a decimal point.
* Example: `age = 25`

Floating-Point Numbers (`float`):

* These are numbers that contain a decimal point.
* Example: `price = 19.99`

Strings (`str`):

* These are sequences of characters enclosed in quotes, used to represent text.
* Example: `name = "Muhammad"`

Booleans (`bool`):

* These represent two values: `True` or `False`.
* Example: i`s_student = True`

Lists (`list`):

* A collection of ordered items that can be of different types, enclosed in square brackets.
* Example: `fruits = ["apple", "banana", "cherry"]`

Tuples (`tuple`):

* Similar to lists, but immutable (cannot be changed after creation) and enclosed in parentheses.
* Example: `coordinates = (10.0, 20.0)`

Dictionaries (`dict`):

* A collection of key-value pairs, where each key is associated with a value, enclosed in curly braces.
* Example: `person = {"name": "Muhammad", "age": 25}`

Sets (`set`):

* An unordered collection of unique items, enclosed in curly braces.
* Example: `unique_numbers = {1, 2, 3}`

None (`NoneType`):

* Represents the absence of a value or a null value.
* Example: `data = None`

### Variable Naming Rules

### When naming variables in Python, there are specific rules you must follow:

1. Start with a Letter or Underscore:
2. Variable names must begin with a letter (a-z, A-Z) or an underscore (\_).
   * Example: `name`, `_name`, `Name123`.
3. No Spaces Allowed:
4. Spaces are not allowed in variable names. Instead, you can use underscores to separate words.
   * Example: `first_name`, `total_price`.
5. Case-Sensitive:
6. Python is case-sensitive, which means `name`, `Name`, and `NAME` are three different variables.
7. Use Alphanumeric Characters and Underscores Only:
8. You can only use letters, numbers, and underscores in variable names. Special characters like @, #, $, etc., are not allowed.
   * Example: `age2`, `user_name`, `data_value`.
9. No Reserved Words:
10. You cannot use Python's reserved words (keywords) as variable names. Keywords are special words that Python uses for its syntax, such as `if`, `else`, `while`, `for`, `break`, `class`, `def`, etc.

### Assigning Values to Variables

In Python, assigning a value to a variable is straightforward. You use the `=` operator to assign a value to a variable.

#### Example 1: Assigning a Single Value

```python
age = 25
name = "John"
height = 5.9

# Printing the values to display them in the console
print("Age:", age)
print("Name:", name)
print("Height:", height)

```

In this example:

* The variable `age` is assigned the integer value `25`.
* The variable `name` is assigned the string value "`John`".
* The variable `height` is assigned the float value `5.9`.

#### Example 2: Assigning Multiple Variables in One Line

```python
x, y, z = 10, 20, 30
```

## Basic Operators

### Arithmetic Operators

> Python Arithmetic Operators are symbols in Python programming that represent basic mathematical operations performed on numeric data types such as integers, floating-point numbers, and complex numbers.

| Operator | Operation      | Example       |
| -------- | -------------- | ------------- |
| +        | Addition       | 5 + 2 = 7     |
| -        | Subtraction    | 4 - 2 = 2     |
| \*       | Multiplication | 2 \* 3 = 6    |
| /        | Division       | 4 / 2 = 2     |
| //       | Floor Division | 10 // 3 = 3   |
| %        | Modulo         | 5 % 2 = 1     |
| \*\*     | Power          | 4 \*\* 2 = 16 |

Example

```python
a = 7b = 2
# addition
print ('Sum: ', a + b)  
# subtraction
print ('Subtraction: ', a - b)   
# multiplication
print ('Multiplication: ', a * b)  
# division
print ('Division: ', a / b) 
# floor division
print ('Floor Division: ', a // b)
# modulo
print ('Modulo: ', a % b)  
# a to the power b
print ('Power: ', a ** b)   
```

### Comparison Operators

> Comparison  in Python are used to compare variables with values.

The comparison operator comes in between the left and right variables or operands. It simply tells us the relationship between the two.

Comparison operatorsComparison operators in Python include:

* Equal to `==`
* Not equal to `!=`
* Greater than `>`
* Less than `<`
* Greater than or equal to `>=`
* Less than or equal to `<=`

Equal to (`==`): Checks if two values are equal.

```python
x = 5
y = 5
print(x == y)  # True
```

Not equal to (`!=`): Checks if two values are not equal.

```python
x = 5
y = 3
print(x != y)  # True
```

Greater than (`>`): Checks if the left value is greater than the right.

```python
px = 5
y = 3
print(x > y)  # True
```

Less than (`<`): Check if the left value is less than the right.

```python
x = 5
y = 7
print(x < y)  # True
```

Greater than or equal to (`>=`): Checks if the left value is greater than or equal to the right.

```python
x = 5
y = 5
print(x >= y)  # True
```

Less than or equal to (`<=`): Check if the left value is less than or equal to the right.

```python
x = 5
y = 6
print(x <= y)  # True
```

### Logical Operators:

> These operators combine or modify Boolean expressions (True/False) to create more complex conditions.

`and`: Returns `True` if both statements are true.

`or`: Returns `True` if at least one of the statements is true.

`not`: Reverses the result of a condition (True becomes False and vice versa).

```python
x = 5
y = 10
# 'and' operator: Both conditions must be true
if x > 3 and y > 8:   
 print("Both conditions are True")  # Output: Both conditions are True
# 'or' operator: At least one condition is true
if x > 6 or y > 8:   
 print("At least one condition is True")  # Output: At least one condition is True

# 'not' operator: Reverse the result
if not x > 10:  
  print("x is not greater than 10")  # Output: x is not greater than 10
```

### Assignment Operators:

> Assignment operators are used to assign values to variables.

* `=`: Assigns value to a variable.
* `+=`: Adds a value to the current value of the variable.
* `-=`: Subtracts a value from the current value of the variable.

Example:

```python
x = 5
  # '=' assigns 5 to x
 x += 3  # '+=' adds 3 to x (x becomes 8)
 x -= 2  # '-=' subtracts 2 from x (x becomes 6)
 print(x)  # Output: 6
```

### Bitwise Operators:

> Bitwise operators work on bits and perform bit-by-bit operations.

* `&`: Bitwise AND
* `|`: Bitwise OR
* `^`: Bitwise XOR
* `~`: Bitwise NOT
* `<<`: Left shift
* `>>`: Right shift

```python

x = 5  # 5 in binary is 101
y = 3  # 3 in binary is 011
# '&' performs bitwise AND
print(x & y)  # Output: 1 (101 & 011 = 001)
# '|' performs bitwise OR
print(x | y)  # Output: 7 (101 | 011 = 111)
# '^' performs bitwise XOR
print(x ^ y)  # Output: 6 (101 ^ 011 = 110)
```

***

### Identity Operators:

> Identity operators check if two variables point to the same object in memory.

* `is`: Returns `True` if both variables point to the same object.
* `is not`: Returns `True` if both variables do not point to the same object.

Example:

```python
x = [1, 2, 3]y = xz = [1, 2, 3]
print(x is y)    
  # True (both x and y point to the same list)
 print(x is not z)  
 # True (x and z point to different lists, even though they have the same content)
```

***

### Membership Operators:

> Membership operators check if a value exists in a sequence like a list, string, or tuple.

* `in`: Returns `True` if the value is found in the sequence.
* not `in`: Returns `True` if the value is not found in the sequence.

Example:

```python
my_list = [1, 2, 3, 4, 5]
# 'in' checks if the value is in the list
print(3 in my_list)  # Output: True
# 'not in' checks if the value is not in the list
print(6 not in my_list)
  # Output: True
```

## Control Flow:

> Control flow is the order in which individual statements, instructions, or function calls are executed or evaluated. The control flow of a Python program is regulated by conditional statements, loops, and function calls.

### Conditional Statements: `if`, `elif`, `else`

Conditional statements allow you to make decisions in your code based on certain conditions.

* `if`: Executes a block of code if the condition is true.
* `elif`: Checks another condition if the previous condition(s) were false.
* `else`: Executes a block of code if all previous conditions were false.

Example:

```python
age = 18
if age < 18:   
 print("You are a minor.")
elif age == 18:  
  print("You just turned 18!")
 else:   
  print("You are an adult.")
```

Output:

```python
You just turned 18!
```

***

### Loops in Python: `for`, `while`

> Loops allow you to repeat a block of code multiple times.

### `for Loop`:

> Used to iterate over a sequence (like a list, tuple, string, or range).

Example:

```python
numbers = [1, 2, 3, 4, 5]
for num in numbers: 
   print(num)
```

Output:

```python
1
2
3
4
5
```

### `while Loop`:

> Repeats a block of code as long as the condition is true.

Example:

```python
i = 1
while i <= 5:  
  print(i)   
  i += 1  # Increment i to avoid infinite loop
```

Output:

```python
1
2
3
4
5
```

### Loop Control Statements: `break`, `continue`, `pass`

> These statements help control how the loop executes.

### `break`:

> Exits the loop when a certain condition is met.

Example:

```python
for i in range(1, 6):  
  if i == 3:      
   break 
   # Exits the loop when i is 3   
   print(i)
```

Output:

```python
1
2
```

### `continue`:

> Skips the current iteration and moves to the next iteration of the loop.

Example:

```python
for i in range(1, 6):  
  if i == 3:        
 continue  # Skips the iteration when i is 3   
  print(i)
```

Output:

```python
1
2
4
5
```

### `pass`:

> A placeholder that does nothing, used when a statement is required syntactically but you don’t want to execute any code.

Example:

```python
for i in range(1, 6): 
   if i == 3:      
  pass  
 # Does nothing   
  print(i)
```

Output:

```python
1
2
3
4
5
```

## Function:

### Defining a Function:

> A function is a block of code that performs a specific task. You define a function using the def keyword followed by the function name and parentheses.

Example:

```python
def greet():    
print("Hello, World!")
```

### Calling a Function:

> To execute the code inside a function, you need to call it by its name followed by parentheses.

Example:

```python
# Defining the function
def greet(): 
   print("Hello, welcome to Python!")
# Calling the function
greet()
```

### Function Arguments:

> In Python, when calling a function, you can pass information (arguments) to it. These arguments can be passed in different ways:

### a) Positional Arguments:

These are arguments that are passed to a function based on their position.

Example:

```python
def greet(first_name, last_name):    
print("Hello, " + first_name + " " + last_name)
# Passing arguments by position
greet("John", "Doe")  
# Output: Hello, John Doe
```

### b) Keyword Arguments:

> These arguments are passed by explicitly naming them, making the order of the arguments irrelevant.

Example:

```python
def greet(first_name, last_name):   
 print("Hello, " + first_name + " " + last_name)
# Passing arguments by keyword
greet(last_name="Doe", first_name="John")  
# Output: Hello, John Doe
```

### c) Default Arguments:

> You can assign default values to arguments. If no argument is provided, the default value is used.

Example:

```python
def greet(first_name, last_name="Smith"): 
   print("Hello, " + first_name + " " + last_name)
# Using default value for 'last_name'
greet("Alice")  # Output: Hello, Alice Smith
# Overriding the default value
greet("Alice", "Johnson") 
 # Output: Hello, Alice Johnson
```

### d) Variable-Length Arguments:

> Sometimes, you may not know how many arguments will be passed to the function. You can use `*args` for positional variable-length arguments or `**kwarg`s for keyword variable-length arguments.

* \*`args`: Used to pass a variable number of non-keyword arguments.
* \*\*`kwargs`: Used to pass a variable number of keyword arguments.

Example with \*`args`:

```python
def sum_numbers(*numbers):  
  total = 0  
   for num in numbers: 
         total += num  
    print("Sum:", total)
# Passing a variable number of arguments
sum_numbers(1, 2, 3, 4)
  # Output: Sum: 10
```

Example with \*\*`kwarg`s:

```python
def display_info(**info):    
for key, value in info.items():   
     print(f"{key}: {value}")
# Passing a variable number of keyword arguments
display_info(name="Alice", age=25, city="New York")
# Output:
# name: Alice
# age: 25
# city: New York
```

***

## Return Statement:

> The `return` statement is used in a function to send a result back to the caller and exit the function.

Example:

```python
def add_numbers(a, b):  
  return a + b
# Calling the function and storing the returned value
result = add_numbers(5, 3)
print(result)  # Output: 8
```

* The `return` the statement returns the sum of `a` and `b` to the place where the function was called.

***

## Lambda Functions:

> A lambda function is a small anonymous function defined using the `lambda` keyword. It can have any number of arguments but can only contain a single expression.

Syntax:

```python
lambda arguments: expression
```

Example:

```python
# Regular function
def add(a, b):    
return a + b
# Lambda function (short version)
add_lambda = lambda a, b: a + b
# Calling the lambda function
print(add_lambda(3, 4))  # Output: 7
```

### Lambda with other functions:

> You often see lambda functions used with functions like `map()`, `filter()`, etc.

Example with `filter()`:

```python
numbers = [1, 2, 3, 4, 5, 6]
# Using lambda to filter even numbers
even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
print(even_numbers)  # Output: [2, 4, 6]
```

## Practice Projects

1. **Simple Calculator**
   * **Skills Covered:** Arithmetic Operators, Functions, Control Flow (if, Elif, else)
   * **Description:** Built a simple calculator that performs basic operations such as addition, subtraction, multiplication, and division using user inputs.
2. **Number Guessing Game**
   * **Skills Covered:** Python Variables, Conditional Statements (if, Elif, else), Loops (While), Logical Operators
   * **Description:** Developed a number guessing game where the user attempts to guess a random number generated by the program, with feedback provided based on the guess.
3. **To-Do List Application**
   * **Skills Covered:** Lists, Functions, Loops
   * **Description:** Created a text-based to-do list where users can add, remove, and view tasks, helping track their daily activities.
4. **Temperature Converter**
   * **Skills Covered:** Functions, Basic Operators, Input/Output
   * **Description:** Designed a temperature converter that converts temperatures between Celsius, Fahrenheit, and Kelvin based on user input.
5. **Basic Inventory Management System**
   * **Skills Covered:** Dictionaries, Conditional Statements, Functions
   * **Description:** Implemented a simple inventory system that allows users to add, remove, and check stock levels of items in a store using a dictionary to store item data.
6. **Multiplication Table Generator**
   * **Skills Covered:** Loops (For), Arithmetic Operators, Input Handling
   * **Description:** Built a program that generates and displays the multiplication table for any number the user provides.
7. **Simple Grading System**
   * **Skills Covered:** Conditional Statements, Comparison Operators
   * **Description:** Developed a grading system that calculates grades based on user input and provides student performance feedback.
8. **Simple Password Generator**
   * **Skills Covered:** Strings, Loops, Functions
   * **Description:** Created a password generator that generates a random password based on user-defined parameters such as length and complexity.
9. **Unit Converter (Length, Weight, Temperature)**
   * **Skills Covered:** Functions, Conditional Statements
   * **Description:** Built a unit converter that allows users to convert between different units like kilometers to miles, kilograms to pounds, and Celsius to Fahrenheit.
10. **Basic Quiz Application**
    * **Skills Covered:** Lists, Loops, Conditional Statements
    * **Description:** Developed a simple quiz program that asks users multiple-choice questions, tracks their answers, and provides the final score.

\ <mark style="color:purple;">Intermediate Python Notes:-</mark>
----------------------------------------------------------------

## Data Structures in Python

> **Data Structures** are ways to store and organize data in a program so it can be used efficiently. Python provides several built-in data structures like lists, tuples, dictionaries, and sets.

### **1. Lists**

A **list** is a collection of items in a particular order. You can change or modify the items in a list.

* **Accessing Elements**: You can get any element in a list by its position (index).
* **Modifying Elements**: You can change items in a list by specifying the index and assigning a new value.
* **Methods**: Lists have useful methods like `.append()`, `.remove()`, `.sort()`, etc.

Example:

```python
my_list = [1, 2, 3]
print(my_list[0])  # Access first element
my_list[0] = 10  # Modify the first element
my_list.append(4)  # Add a new element to the list
print(my_list)  # Output: [10, 2, 3, 4]
```

### **2. Tuples**

A **tuple** is similar to a list but is **immutable**, meaning you cannot change its elements after it's created.

* **Accessing**: Just like lists, you can access tuple elements by index.
* **Immutable Nature**: Once defined, elements cannot be added, removed, or changed.

Example:

```python
my_tuple = (1, 2, 3)
print(my_tuple[0])  # Access first element
# my_tuple[0] = 10  # This will cause an error as tuples are immutable
```

### **3. Dictionaries**

A **dictionary** stores data in key-value pairs.

* **Accessing**: You access values using their keys.
* **Modifying**: You can add, change, or remove key-value pairs.
* **Methods**: Useful methods include `.keys()`, `.values()`, `.items()`.

Example:

```python
my_dict = {"name": "Alice", "age": 25}
print(my_dict["name"])  # Access value by key
my_dict["age"] = 26  # Modify a value
my_dict["city"] = "New York"  # Add a new key-value pair
print(my_dict)  # Output: {'name': 'Alice', 'age': 26, 'city': 'New York'}
```

### **4. Sets**

A **set** is a collection of unique elements.

* **Operations**: You can perform operations like union, intersection, and difference on sets.
* **Modifying**: You can add or remove elements in a set.
* **Methods**: Common methods include `.add()`, `.remove()`, `.union()`, `.intersection()`.

Example:

```python
my_set = {1, 2, 3}
my_set.add(4)  # Add an element
my_set.remove(2)  # Remove an element
print(my_set)  # Output: {1, 3, 4}
```

## String Manipulation

Strings are sequences of characters in Python. You can modify and perform operations on them.

### **1. String Operations**

You can concatenate strings, repeat them, and check their length.

Example:

```python
greeting = "Hello"
name = "World"
message = greeting + " " + name  # Concatenation
print(message)  # Output: "Hello World"
```

### **2. String Methods**

Python provides built-in methods for strings like `.upper()`, `.lower()`, `.replace()`, etc.

Example:

```python
text = "hello"
print(text.upper())  # Output: "HELLO"
```

### **3. Formatting Strings**

You can format strings using placeholders.

Example:

```python
name = "Alice"
age = 25
print(f"My name is {name} and I am {age} years old.")  # Output: "My name is Alice and I am 25 years old."
```

### **4. String Slicing**

You can extract parts of a string using slicing.

Example:

```python
word = "Python"
print(word[0:2])  # Output: "Py"
```

## File Handling

Python provides ways to handle files for reading and writing.

### **1. Opening and Closing Files**

To work with files, you must first open them. Once done, you should close them.

Example:

```python
file = open("example.txt", "r")
# Perform operations
file.close()
```

### **2. Reading Files**

You can read a file’s content using `.read()`, `.readline()`, or `.readlines()`.

Example:

```python
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

### **3. Writing to Files**

You can write data to a file using `.write()`.

Example:

```python
with open("example.txt", "w") as file:
    file.write("Hello, World!")
```

### **4. File Modes**

* `'r'`: Read mode
* `'w'`: Write mode (overwrites the file)
* `'a'`: Append mode (adds to the file)

### **5. Handling Exceptions with Files**

You can handle errors during file operations using exception handling.

Example:

```python
try:
    file = open("example.txt", "r")
    content = file.read()
except FileNotFoundError:
    print("File not found.")
finally:
    file.close()
```

## Exception Handling

Exceptions are errors that occur during the execution of a program.

### **1. Understanding Exceptions**

When an error occurs, an exception is raised, and the program stops unless handled.

### **2. Try, Except Block**

You can use `try` and `except` to handle exceptions and prevent program crashes.

Example:

```python
try:
    print(10 / 0)
except ZeroDivisionError:
    print("Cannot divide by zero.")
```

### **3. Finally Block**

The `finally` block runs code regardless of whether an exception occurs.

Example:

```python
try:
    print(10 / 2)
finally:
    print("This will always execute.")
```

### **4. Raising Exceptions**

You can raise exceptions manually using `raise`.

Example:

```python
eif age < 18:
    raise ValueError("Age must be 18 or older.")
```

### **5. Handling Multiple Exceptions**

You can handle different exceptions using multiple `except` blocks.

Example:

```python
try:
    print(10 / 0)
except ZeroDivisionError:
    print("Division error.")
except ValueError:
    print("Value error.")
```

## Modules and Packages

A **module** is a Python file containing code (functions, variables, etc.). A **package** is a collection of modules.

### **1. Importing Modules**

You can import modules using `import`.

Example:

```python
import math
print(math.sqrt(16))  # Output: 4.0
```

### **2. Standard Library Modules**

Python has many built-in modules like `math`, `datetime`, and `random`.

### **3. Creating and Using Custom Modules**

You can create your own module by writing Python code in a `.py` file.

Example:

```python
# mymodule.py
def greet():
    print("Hello!")
```

### **4. Understanding Packages**

A package is a directory with multiple modules, and it includes an `__init__.py` file.

### **5. Installing External Packages with pip**

You can install external packages using `pip`, Python's package manager.

Example:

```bash
pip install requests
```

## Object-Oriented Programming (OOP)

**OOP** is a programming style where you create objects that have attributes (properties) and methods (functions).

### **1. Introduction to OOP Concepts**

OOP focuses on classes and objects. A **class** is a blueprint for creating objects.

### **2. Classes and Objects**

You define a class and create objects from it.

Example:

```python
class Dog:
    def __init__(self, name):
        self.name = name

dog1 = Dog("Buddy")
print(dog1.name)  # Output: Buddy
```

### **3. Constructors**

A **constructor** is a special method called when an object is created, defined by `__init__()`.

### **4. Inheritance**

**Inheritance** allows one class to inherit properties from another.

Example:

```python
class Animal:
    def speak(self):
        print("Animal sound")

class Dog(Animal):
    def speak(self):
        print("Bark")

dog = Dog()
dog.speak()  # Output: Bark
```

### **5. Encapsulation**

**Encapsulation** is the idea of hiding data inside objects and only exposing what’s necessary.

### **6. Polymorphism**

**Polymorphism** allows objects of different types to be treated as if they are of the same type.

### **7. Method Overriding**

You can **override** a method in a child class that was defined in the parent class, like the `speak()` method above.
