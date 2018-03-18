# Python Workshop 2018


## Introduction


Hello, I hope everyone was able to download and install python and your choice of text editor. If for some reason that is not the case, you can see our helpful friends in the blue t-shirt. Please approach them or raise your hand, they’ll come and solve any issues you’re facing. So let’s get the learning started. I have to start off by introducing myself to you and then later on also have to introduce you to python. So I thought why not do both of them together. I'll introduce myself through a python code.

## Hello Code

Welcome to IEEE Python Workshop 2018 edition. It's my pleasure to conduct today's workshop for you.
My name is Saurabh Mudgal.
I am 19 years old and am majoring in mechanical engineering.

I believe this is the first programming experience for most of you. If you look at the introductory code, the output is displayed in English and is readable and the sentence makes some sense. However, if you look at the input code you will find there is a code written to which is really different from the output. And I promise you that if you can lend me your patience for the next hour working with such codes will be a child's play for you.

You will notice the word "name" is set as equal to an arithmetic calculation. The word age, in the code is an example of a variable, like the x and y variables in math. In programming, a variable is used to store and referance information. A variable doesn't have to be made of a single letter. In python it can be made up of any combinations of letters, given they are aplphanumeric characters or the underscore character. 

You can also see the equal two sign. This is an operator. Operators run operations on variables and include plus, minus, multiplication, division, and the remainder operation with the symbol %.  Now in programming, this is actually termed as assignment. The variable is by convention on the left side of the equal to sign and is assigned the value that is on the right side of the equal to sign. So the code instructs the computer to first compute the arithmetic result on the right and the assign the value to the variable age. The order this proceeds is first carrying out the multiplication operation in the bracket which results 30. Then it carries out the remainder operation inside the bracket, which gives 2. Next it divides 30 by to 2 result 15. Then adds 5,2 and 15 to give 21. Finally it subtracts 2 to give 19. This arithmetic result is saved in variable age. The code conventionally follows al list of preferances for operators. The operator with the higher preferance is executed first and so on.

Since, the variable  age holds a numeric value, it is termed as a numeric variable type.

Next you can see "greeting" is equal to a whole sentance. The value on the right side is a string type. Strings is basically the term given to a collection of words. A string in python is a array of alphanumeric letters contained in quotation marks, which can be either single or double.

Since the value assigned to variable "greetings" is of string type, "greetings" is a string type variable. The same is also true for the variable "name" and "major".

Its worth noting that python 3 is executed line-by line in a sequential fashion. So a string length is limited to one line. However, if you want to create multi-line strings in python, this can be achieved using the  quotes thrice to enclose the string instead of just once. The quotes can be single or double, but the point is they need to be three times on both ends of the strings.

Getting back to the code, you can notice the word print followed by brackets enclosing some text. This is the commonly used print function, which used to print or display output on the screen. It prints whatever string is enclosed in the brackets. So you can see that simply putting "greetings" in the bracket directs the computer to print the string value contained in the string variable "greetings.

The print function in line 7 is used to print an output string that is formed of different types of instructions. What I mean by this is that print function is first instructed to print the string that is typed in the brackets. Next it is instructed to print the string value contained in the string function "name" and then the following string typed in brackets. Note that the plus signs are very important here. They instruct the computer that there is continuity in the output and it should print as one single string or sentance.
Also, it is necessary to prevent the code from running into a syntax error. Syntax errors will be explored later on but can be thought of as grammatical mistakes in the python language.

Also note in line 8, the print function contains "str(age)". This process in programming is called as typecasting and str() bracket is called a format specifier. A string format specifier in this case. Putting age in str brackets, cast the string type value on an otherwise numeric variable. Hence it allows the numeric value of number 19 contained in variable "age" to be displayed in the string or sentance as the letter 19. Otherwise, if all value types in print are not string type, the code might again run into a syntax error.

## Syntax

When you're learning a coding language it's like learning any Spanish or French for the first time. You have to learn the grammar (syntax), the conventions (types and variables), the phrases (library/ classes/ functions) and above all you have to practice. Similarly when coding, you have to practice correct syntax. The syntax of a programming language is the set of rules that defines the combinations of symbols that are considered to be correctly structured pieces of code.

## What is a code and why do we need it?

So now that you have seen you're first code, I think we can define it. In easy words, a code is a set of instructions that tells the computer to do something. It sends detailed and exact instructions to the computer which are needed to solve a specific problem. These instructions are written using a programming language like python.

But why do we need to code? Why do we need python in the first place? This is because a language barrier exists between humans and the machinery or computers. Computers can't understand English or Spanish or any other human language. The only language they understand is the binary language. Unlike English, which uses combinations of 26 alphabets to build words, binary language is very hard to read because it represents words or data as a combination of only two digits, 1 and 0. You can learn more about this in your own time but for the purposes of this workshop, you just need to know that binary language is not easily interpreted by humans.

## Code to Binary

Now you might say that hey but the code we just saw was also written in English. So how do the alphabets of the code get converted to binary language 1s and 0s. This job is carried out by your IDE, integrated development environment. The IDE I'm using right now and most of you might have seen in the installation instruction video is Komodo Edit 11. The process through which the code is translated to binary language is called compiling. The compiling ability of an IDE is part of why we type our code there and not just in a word document.

## Libraries

This is followed by the process of linking, in which the IDE links your code to libraries. In programming, a library is a collection of precompiled routines that a program can use. In python, to include a library in your code just type import followed by the library's name. However, you should be careful to write this before any other line of code. In the example below, the "platform" library is linked to the code. This allows the code to use platform.python_version() function. Also note, there is a line of text before the import platform statement. This is coloured grey because this is a comment. Anything in a line that is followed by a #, is excluded from the code and is only present as a comment. The hash is an indicator to the computer that this is a comment and should be overlooked. 

## Types and Values
> example 2
> bool type
> sequence type
> type() and id()

## Python

### Points

So why  python. Python is a tool at the disposal of human beings to interact with the computers and machinery. It is a tool through which humans can use to tell the computers to do something. So, the language we understand is English, the language computers understand is binary and Python can be thought of as mediator language that can be easily comprehended by humans and can be effectively translated to binary language. 

What merit does it have over other programming languages. Python is known for its remarkable power yet a readable syntax. It is one of the easiest programming languages to learn but is also one of the most powerful languages, used heavily in machine learning and data science.

### History

Python was developed in the 1980s by Dutch programmer Guido van Russom. There's a core philosophy behind the Python language, which includes the following statements: Beautiful is better than ugly.

It's always a good idea to make your code elegant and readable. Explicit is better than implicit. Don't make your readers guess what your code does, make it obvious. Simple is better than complex. If you can make it simple, do. Readability counts. As a casual reader with a good understanding of the Python language, you should be able to understand the code with a minimal amount of effort.

Python 3 is very close to Guido's ideal vision for python. This workshop will teach python 3. Note that there is a considerable difference between python 3 and python 2. Python 3 is also isn't backward compatible; which means codes written in python 3 might not be compatible with python 2.

Now, you've had a thorough introduction to programming. Let's proceed to some noteworthy detials of the language. 


## Python Applications

Python has potential applications in an array of fields:

### Surveying

Python is a widely popular platform for developing surveying softwares and data analysis. A basic principle behind these applications is the ease with which data can be collected.

By putting the string in the input bracket we instruct the computer to record the value entered after the string is displayed as input and typecast it to integer type and then sace it in the variable a.

In only one line of code it can ask for data, capture it and assign it to the desired variable. The compactness and conciseness of the code makes it especially powerful over other coding languages.

A more complex code strip can be added to these statements to also on-the-spot analyse data, present results or predictions and make suggestions. Such a complex code will require more attention than just an hour and can't be discussed today. However, for your referance, I'll make sure to send you some post-workshop resources which will contain such codes.

### Finance

Finance industry, for example, can save large chunks of time by using pre-written python codes to carry out calculations and tabulations. In addition to the arithmetic operators, python also has a large set of mathmatical functions that it can apply to input data. Hpwever, due to the very nature of programming a problem persists. An over-simplified of the codes is presented below.

By applying simple logic we will know that 0.1  0.1 + 0.1 - 0.3 will be equal to zero. However, if this operation is carried out in python it will result in a value that is very close to zero but not exactly zero. This is because computer programmes save 0.1 accurate upto say 15 decimal points depending upon the value type. However after 15 decimal points there are random numbers filled in to infinity which vary from 0-9. Computer programmes trade of accuracy for higher precision. To solve this issue while financing or doing calculations involving money we use this statement:

from decimal import *

This basically instructs the computer to import a particular function from the class decimal. This enables us to use Decimal format specifier. What we are doing is taking a string 0.10 and converting that to numeric type but only upto two decimal points. So we decrease the precision while increasing the accuracy. Hence by using these values in our calculations leads to the accurate result zero. 

## Conclusion

Classes and functions will be discussed in depth in tommorow's workshop and i encourage you to especially attend that.That is time for me. I hope I have equipped you with some basic knowledge of python that is of use for you. Thank you for your patience and attention.
