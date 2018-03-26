# IEEE-Python_Workshop-2018
*by Saurabh Mudgal for IEEE NTU Student Branch*

*__Disclaimer:__ This document is meant to serve as a reference for the attendees of IEEE Python Workshop 2018. It does not cover all concepts and implementations discussed in the workshop.*


## Hello!

Welcome to a condensed introduction to Python 3. Kindly, refer to `Installing_Python3.md` since you'll need to install python 3 on your devices before you can start learning coding. For improved understanding, it's recommended that while reading through this document you read `Script.md` simultaneously. Following is the output for the code:

> Welcome to IEEE Python Workshop 2018 edition. It's my pleasure to conduct today's workshop for you.

>My name is Saurabh Mudgal.

>I am 19.0 years old and am majoring in mechanical engineering.

If you wish to display the aforementioned output as text on the computer screen the following python code should be written and executed:

```python 3
age = 5+(8%3)-3+(3*10)/2

greetings = 'Welcome to IEEE Python Workshop 2018 edition. It's my pleasure to conduct today's workshop for you.'

name = 'Saurabh Mudgal'

major = 'mechanical engineering'


print(greetings)

print('My name is ' + name + '.')

print('I am ' + str(age) + ' years old and am majoring in ' + major + '.')
```

## Types and Values

There are two main pre-defined types of variables (although python alows you to create your own variable types):

* Numeric types
* String types

```Python 3                            
a = 9                                 # a is numeric type
b = 9.12                              # b is numeric type
c = 3/2                               # c is numeric type
d = 'Apple'                           # d is string type
e = 'Goodevening! Nice to meet you'   # e is string type
```

## Basic Syntax

__What is Syntax?__

In python, syntax refers to the rules that specify the correct combined sequence of symbols that can be used to form a correctly structured program using python. Programmers communicate with computers through the correctly structured syntax, semantics and grammar of the programming language (In our case, python).

__Statement:__ Each line of code in a Python program is called a statement. Python interprets statements and runs them one by one.

__Comments:__ The `#` symbol indicates a comment and anything after `#` is ignored by the computer. Comments provide information to improve code readability.

__Built-in Functions:__ Python comes with many built-in functions like `print()` & `input()` to help you in writing your code.

## What is a code and why do we need it?

* It sends detailed and exact instructions to the computer which are needed to solve a specific problem.
* These instructions are written using a programming language like python.
* Computers can only communicate in binary language.

## Code to Binary

* An integrated development environment (IDE) is a software application that provides comprehensive facilities to computer programmers for software development.
* We are using Komodo Edit 11.
* IDE process cycle - _compile, link and debug_

## Libraries

* IDE links libraries to the code.
* Libraries give codes access to vast pre-defined functions and classes.
* Work of coders is stored in libraries for use in future codes.

```Python 3
# Below is an example of a library. This is a code to display the version of the python software


import platform

print('This is python version ' + str(platform.python_version())
```

## Python

### Facts

* Python is a tool at the disposal of human beings to interact with the computers and machinery.
* Python is a mediater language.
* Python is known for its remarkable power yet a readable syntax. 
* It is one of the easiest programming languages to learn but is also one of the most powerful languages, used heavily in machine learning and data science.

### History

* Python was developed in the 1980s by Dutch programmer Guido van Russom
* There's a core philosophy behind the Python language, which includes the following statements:
    1) Beautiful is better than ugly.
    2) Explicit is better than implicit.
    3) Simple is better than complex.
    4) Readability counts.
* Python 3 isn't backward compatible. It is very different from earlier versions.

## Python Applications

Python has potential applications in an array of fields:

### Surveying

Python is a widely popular platform for developing surveying softwares and data analysis.

```Python 3
a = int(input('Enter your content with the workshop content (On a scale 1-10): '))

print('The workshop is ' + str(10*a) + '% effective.')
```

### Finance

In addition to the arithmetic operators, python also has a large set of mathmatical functions and tabulation features that it can apply to organise data.

Limitation of python code:

```Python 3
x = 0.1 + 0.1 + 0.1 - 0.3

print("x = " + str(x))
```

> x = 5.551115123125783e-17

Alternative solution/ Improvement to the code:

```Python 3
from decimal import *

a = Decimal('0.10')
b = Decimal('0.30')

x = a + a + a - b

print('x = ' + str(x))
```

> x = 0

### Additional areas benefiting from python applications

* account management
* insurance
* payment processing
* regulation
* capital markets
