**1. Description**
A Python console program that performs basic arithmetic operations—addition, subtraction, multiplication, and division. The calculator allows users to chain calculations (continue with a result) or start a fresh calculation anytime. Mathematical functions are mapped to operator symbols and selected interactively by the user.

**2. How It Works**
The program prints a logo at the start.

The user inputs the first number.

All available operation symbols (+, -, *, /) are displayed.

The user chooses an operation and enters the next number.

The calculation result is displayed.

The user can continue calculating with the previous result or start a new calculation (recursion).

The process can be repeated indefinitely.


**3. Operators and Functions Used**

Operators:
= (Assignment): Stores values for variables (e.g., inputs, results, flags).

+, -, *, / (Arithmetic): Performs addition, subtraction, multiplication, and division.

in: Used in loops to iterate over dictionary keys and input checks.

[] (Indexing): Fetches functions from the operations dictionary by operator symbol.

: (Colon): Structures blocks for functions, loops, and control statements.



Functions and Methods:
print(): Displays prompts, results, and operation symbols.

input(): Collects user input for numbers, operation choices, and continuation.

float(): Converts string input to floating-point numbers for calculations.

calculator(): Main function handling user interaction and calculation workflow.

for loop: Iterates over available operations for selection.

Recursion: Restarts the calculator when a new calculation is chosen.

User-defined functions: add(), subtract(), multiply(), divide() each return the result of the arithmetic operation.

Dictionary mapping: Links operator symbols to corresponding functions.
