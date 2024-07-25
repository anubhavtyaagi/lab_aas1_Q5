# lab_aas1_Q5
Explanation:
Preprocessor Directive and Header Inclusion:

#define _CRT_SECURE_NO_WARNINGS: This is a Microsoft-specific directive to suppress warnings related to unsafe functions like scanf.
#include <stdio.h>: Includes standard input-output functions for input and output operations.
Function Declarations:

sum(int n1, int n2), minus(int n1, int n2), multiply(int n1, int n2), divide(int n1, int n2): These are function prototypes (declarations) that tell the compiler about the functions' names, return types, and parameters. The actual implementations of these functions are defined later in the code.
Main Function (main()):

Input Handling: Prompts the user to enter two integers (num1 and num2) and an operator (+, -, *, / or q to quit). It uses scanf_s to safely read integers and scanf to read the operator.
Operator Validation: Uses a while loop to ensure that the entered operator is valid (+, -, *, / or q). If not valid, it keeps asking for valid input.
Switch Statement: Depending on the operator entered (+, -, *, /), it calls the respective function (sum(), minus(), multiply(), divide()). If q is entered, it exits the loop.
Function Definitions:

sum(int n1, int n2): Adds n1 and n2 and returns the result.
minus(int n1, int n2): Subtracts n2 from n1 and returns the result.
multiply(int n1, int n2): Multiplies n1 and n2 and returns the result.
divide(int n1, int n2): Divides n1 by n2 (casting n1 to float for floating-point division) and returns the result as a float. Checks for division by zero.
Summary:
The program implements a simple calculator using functions for basic arithmetic operations (+, -, *, /).
It handles user input and validates operator input to ensure correct functionality.
Functions are used to encapsulate the logic of each arithmetic operation, promoting code reusability and readability.
This structure ensures clarity and modularity, making the code easier to understand and maintain.



