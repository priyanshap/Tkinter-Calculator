# Tkinter-Calculator

This code creates a graphical calculator application using Python's tkinter library. Here's a description of its main components and functionality:

## The Calculator class:
Initializes the main window and sets up the user interface.
Creates a display (Entry widget) for showing input and results.
Defines a layout for calculator buttons, including numbers, operators, and special functions.


## Button layout:
Numbers 0-9
Basic operators: +, -, *, /
Parentheses: (, )
Power operation: ^
Square root: √
Clear (C) and equals (=) buttons
A backspace button (Back)


## Functionality:
Clicking number or operator buttons adds them to the expression.
The C button clears the entire expression.
The = button evaluates the expression and displays the result.
The √ button adds a square root function to the expression.
The Back button removes the last character from the expression.
Power (^) is converted to ** for Python's exponentiation operator.
Square root (√) is converted to math.sqrt() for evaluation.


## Error handling:
If an invalid expression is entered, an error message is displayed.


## User Interface:
Buttons are created with a light blue background and a solid border.
The display has a light gray background.
The layout is organized in a grid pattern.

## Preview
![image](https://github.com/priyanshap/Tkinter-Calculator/assets/158167690/b589d1b6-a00b-4afd-a90a-e9a53801cf72)
