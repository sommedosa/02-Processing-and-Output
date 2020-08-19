# Processing, and Output  

**Programs must be designed before they are written**
## Program development cycle:
  * Design the program
  * Write the code
  * Correct syntax errors
  * Test the program
  * Correct logic errors

## Pseudocode: fake code
* Informal language that has no syntax rule 
* Not meant to be compiled or executed
* Used to create model program
  - No need to worry about syntax errors, can focus on program’s design
  - Can be translated directly into actual code in any programming language

## Flowchart: diagram that graphically depicts the steps in a program
* Ovals are terminal symbols
* Parallelograms are input and output symbols
* Rectangles are processing symbols
* Symbols are connected by arrows that represent the flow of the program

## Computer performs three-step process
* Receive input
  - Input: any data that the program receives while it is running
* Perform some process on the input
  - Example: mathematical calculation
* Produce output

## Displaying Output with the print Function
* Function: piece of prewritten code that performs an operation
* Print function: displays output on the screen
* Argument: data given to a function

## Keywords
* Algorithm: set of well-defined logical steps that must be taken to perform a task
* String: sequence of characters that is used as data
* String literal: string that appears in actual code of a program
* Comments: notes of explanation within a program
* End-line comment: appears at the end of a line of cod
* Variable: name that represents a value stored in the computer memory
* Assignment statement: used to create a variable and make it reference data
  - General format is variable = expression
* Garbage collection: removal of values that are no longer referenced by variables
* Data types: categorize value in memory
* Numeric literal: number written in a program
* When + operator used on two strings in performs string concatenation

  
## Rules for naming variables in Python:
* Variable name cannot be a Python key word 
* Variable name cannot contain spaces
* First character must be a letter or an underscore
* After first character may use letters, digits, or underscores
* Variable names are case sensitive


## Data Output
* Print function displays line of output 
  - Newline character at end of printed data
  - Special argument end='delimiter' causes print to place delimiter at end of data instead of newline character
* Print function uses space as item separator
  - Special argument sep='delimiter' causes print to use delimiter as item separator
* Special characters appearing in string literal, preceded by backslash (\)
  - newline (\n), horizontal tab (\t), single quote (\'), double quote (\"), back slash (\\)


## Format display of numbers on screen using built-in format function
Two arguments:
* Numeric value to be formatted
* Format specifier
  - Inserting Comma Separators
  - Specifying a Minimum Field Width
  - Formatting a Floating-Point Number as a Percentage, The % symbol can be used in the format string of format function to format number as percentage
  - Formatting Integers, d
https://pyformat.info/

-------------------

# Exercise2

1.	What would the following display? </br>
  a = 5 </br>
  b = 2 </br>
  c = 3 </br>
  result = a + b * c </br>
  print(result) </br>

2.	Assume the variables result, w, x, y, and z are all integers, </br> 
and that w = 5, x = 4, y = 8, and z = 2. </br>
What value will be stored in result after each of the following statements execute? </br>
   a. result = x + y </br>
   b. result = z * 2 </br>
   c. result = y / x </br>
   d. result = y – z </br>
   e. result = w // z </br>

3.	What would the following display? </br>
   num = 99 </br>
   num = 5 </br>
   print(num)</br>

4.	What will the following statement display? print('X\tO\tX\nO\tX\tO\nX\tO\tX\n')</br>

5.	Write a Python program which accepts the radius of a circle from the user and compute the area. </br>
    Sample Output :</br>
       r = 1.1</br>
       Area = 3.8013271108436504</br>

6.	Write a program that displays the following information: </br>
    • Your name </br>
    • Your address </br>
    • Your nick name</br>

7.	One pound is equivalent to 0.454 kilograms. Write a program that asks the user to enter the mass of an object in pounds and then calculates and displays the mass of the object in kilograms.</br>

8.	Assuming there are no accidents or delays, the distance that a car travels down the interstate can be calculated with the following formula: Distance 5 Speed 3 Time A car is traveling at 70 miles per hour. Write a program that displays the following: • The distance the car will travel in 6 hours • The distance the car will travel in 10 hours • The distance the car will travel in 15 hours</br>
