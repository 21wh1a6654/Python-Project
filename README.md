# Python-Project
Using Gui 
Simple Programming Language Interpreter:

This project is a simple interpreter for a custom programming language described by a basic Backus-Naur Form (BNF). The interpreter accepts valid statements in the language and executes them until a STOP statement is encountered. Once a STOP statement is reached, it prints each variable assigned a value along with its current value.

Language Description
The programming language has the following components:

Variables: A, B, C, and D, represented as single uppercase letters.
Digits: Single digits from 0 to 9.
Operators: Addition (+), represented by a single plus sign.
Expressions: Combinations of variables, digits, and operators.
Statements: Assignment statements in the form <variable> = <expression> or the STOP statement.
Valid Statements Examples
A=4: Assigns the value 4 to variable A.
=33: Assigns the value 33 to an unnamed variable (not supported).
C=A+B: Assigns the sum of variables A and B to variable C.
D=62*P: Assigns the result of the expression 62*P to variable D.
STOP: Stops the execution of the program.
Invalid Statements Examples
K=31: K is not a valid variable.
B=952: Number must be no more than two digits.
C=-A: Unary minus is not defined.
D=A+B*C: Only one operator allowed.
APC: No spaces allowed.
How to Use
To use the interpreter, follow these steps:

Clone the Repository: Clone this repository to your local machine.
git clone https://github.com/your-username/simple-interpreter.git
Run the Interpreter: Execute the interpreter.py script with a valid program as input.
python interpreter.py
Provide Input: Enter the program statements in the console.
\A=5
D=6*A
C=D+60
STOP
View Output: The interpreter will print the variables and their assigned values.
A = 5
D = 30
C = 90
Example
program = """
A=5
D=6*A
C=D+60
STOP
"""
