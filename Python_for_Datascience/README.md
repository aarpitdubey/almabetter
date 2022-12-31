# Python For Data Science

## What is Python?
<br>

* Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. 

* Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together.

* Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. 

* The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

 * Often, programmers fall in love with Python because of the increased productivity it provides. Since there is no compilation step, the edit-test-debug cycle is incredibly fast. 
 
 * Debugging Python programs is easy: a bug or bad input will never cause a segmentation fault. Instead, when the interpreter discovers an error, it raises an exception. When the program doesn't catch the exception, the interpreter prints a stack trace. 
 
 * A source level debugger allows inspection of local and global variables, evaluation of arbitrary expressions, setting breakpoints, stepping through the code a line at a time, and so on. 
 
 * The debugger is written in Python itself, testifying to Python's introspective power. On the other hand, often the quickest way to debug a program is to add a few print statements to the source: the fast edit-test-debug cycle makes this simple approach very effective.
<br><br>
## What are IDE’s, Jupyter Notebook and Anaconda?

Most programmers make use of applications called Integrated Development Environments, or IDEs, that aid the programming process.

* An Integrated Development Environment is a software application that provides comprehensive facilities to computer programmers for software development. 

* An IDE normally consists of at least a source code editor, build automation tools and a debugger.

Jupyter Notebook is an IDE for Python that allows its users to create documents containing both rich text and code. It also supports the programming languages Julia, and R. 

* The term Jupyter is a combination of the words Julia, Python and R and is the IDE of choice for many people using Python because it’s both simple to use and it’s designed for easily distributing your results. This ease of communication is why it’s particularly popular with businesses.

However, Jupyter is not the only IDE used by people coding in Python. More experienced programmers often use an IDE called Spyder, which is closer in design to more typical IDEs used by programmers.

Anaconda is essentially a package that allows us to quickly and correctly install Python, and a range of popular machine learning-based IDEs.

Anaconda is essentially a one-stop-shop data science toolkit. The easiest way to perform Python/R data science and machine learning on a single machine. Developed for solo practitioners, it is the toolkit that equips you to work with thousands of open-source packages and libraries

## What is Google Colab?

Colaboratory by Google (Google Colab in short) is a Jupyter notebook based runtime environment which allows you to run code entirely on the cloud.

This is necessary because it means that you can train large scale ML and DL models even if you don’t have access to a powerful machine or a high speed internet access.

Google Colab supports both GPU and TPU instances, which makes it a perfect tool for deep learning and data analytics enthusiasts because of computational limitations on local machines.

Since a Colab notebook can be accessed remotely from any machine through a browser, it’s well suited for commercial purposes as well.

As a programmer, you can perform the following using Google Colab.

* Write and execute code in Python

* Document your code that supports mathematical equations
 * Create/Upload/Share notebooks

* Import/Save notebooks from/to Google Drive

* Import/Publish notebooks from GitHub
Import external datasets e.g. from Kaggle
Integrate PyTorch, TensorFlow, Keras, OpenCV

* Free Cloud service with free GPU

In the right side of this page, you can explore the integrated IDE for your practice.

```PYTHON
print("Hello World !")
print("I will be a Data Scientist.")
print("Arpit Dubey")
```
Copy the above code snippet and paste in the IDE, choose the mode as Python and click on Run Code.

<br><br>

## Different data types we will encounter in Python

1. <b>Numeric</b> - Numeric variables take values which are numbers like 9, 3.14, 0, Inf

2. <b> String </b> - String variables are used to store textual information

3. <b> Boolean </b> - Boolean variables have two modes either True or False. A definite judge of statements!

4. <b>Datetime</b> - These variables are used to store date and time values such as 2020-08-01 12:23:54


```Python

# Addition
1 + 1 # It will gives 2

# Substraction
10 - 8 # It will gives 2

# Multiplication
2 * 10 # It will gives 20

# Division
10 / 2 # It will return float 5.0 as a result

# Floor Division
10 // 2 # It will return integer 5 as a result

# Exponentiation
10**5 # It will gives 100000

# Modulus
2%10 # It will gives 2

# Order of Operation followed in python
8 + 10 * 10 + 2 # It will gives 110

8 + 10 * (10 + 2) # It will gives 128 

# Scientific Notation for representing large numbers
5E6 # It will gives 5000000.0

1E2 # It will gives 100.0

# Avagardo constant is 6E23
```

## What is a Variable?

* Variable are the entities which help us to store information and retrieve it later.

* It stores information of nature like numeric, textual, bool etc.,

* A Python variable is a reserved memory location to store values. In other words, a variable in python program gives gives data to the computer for processing

* The type() of data contained in the Python variable can be changes at user's will.

```Python

x = 10
y = 20

print(f"x = {x} and, y = {y}") # x = 10 and, y = 20

# Avagardo constant
avagardo_constant = 6E23

print(f"Avagardo Constant = {avagardo_constant}") # Avagado Constant = 6e+23, means python interpreter won't write all the 0's. the number is 600000000000000000000000.0 

# Addition
z = x + y

print(f"z = {z}") # z = 30

# Printing the memory address the variable z occupies
print(hex(id(z))) # It will gives:  0x190a5c645f0 or different memory location

# Substraction

z = y - x
print(f"z = {z}") # z = 10
type(z) # float, type() gives the data type of variable z

# Multiplication
z = x * y
print(f"z = {z}") # z = 200.0
type(z) # float, type() gives the data type of variable z

# Division
z = y / x
print(f"z = {z}") # z = 2.0
type(z) # float

# Floor Division
z = y // x
print(f"z = {z}") # z = 2
type(z) # Int

# Modulus

z = y % x
print(f"z = {z}") # z = 2

# Using Power and exponent
z = x ** y
print(f"z = {z}") # z = 100000000000000000000

```

## Rules for naming a variable in Python

* Variable name must start with a letter (or) an underscore like " _", "product", "_product", (or) "product_"

* The reminder of your variable name may consist of letters, numbers and underscores

* spacy1, pyThon, machine_learning are some valid variable names

* Names are case sensitive.

* case_sensitive, CASE_SENSITIVE, and Case_Sensitive are each a different variable.

```PYTHON
1plus10 = "OnePlusTen Mobile phone" # It will throws SyntaxError : Invalid syntax because it starts with a numeric value

OnePlus10 = "OnePlusTen Mobile phone" # It's a valid syntax

_1plus10 = "OnePlusTen Mobile phone" # It will alsao not throws any error because it start with "_" underscore

list = 10 # It will also not throws any error but "list" is a reserved keyword in python so, using a python pre-defined keyword as variable name is not a good practice.
```

* Variable names cannot begin with a number

* Name can not contain spaces, use _ instead

* Names can not contain any of these symbols: 
```:'",<>/?|\!@#%^&*()+=`~:```

* It is consider a best practice that names are in lowercase with _ underscore.

* Avoid using python built-in keywords like ```list, str, def ... etc.```