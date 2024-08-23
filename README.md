# Operators:
Aim:
To understand and demonstrate the use of arithmetic operators in C++. This includes performing basic mathematical operations such as addition, subtraction, multiplication, division, and modulus, and observing their effects on numerical data.

Theory:
Arithmetic operators in C++ are used to perform basic mathematical operations:

Addition (+): Adds two operands.
Subtraction (-): Subtracts the second operand from the first.
Multiplication (*): Multiplies two operands.
Division (/): Divides the first operand by the second (note integer division truncates the result).
Modulus (%): Returns the remainder of the division of the first operand by the second.
These operators are essential for performing calculations and manipulating numeric data in various programming tasks.

Procedure:
Include Required Headers:

#include <iostream>
using namespace std;
Define Main Function:


int main() {
    // Declare variables
    int num1, num2;

    // Input values from user
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Enter second number: ";
    cin >> num2;

    // Perform arithmetic operations
    cout << "Addition: " << num1 + num2 << endl;
    cout << "Subtraction: " << num1 - num2 << endl;
    cout << "Multiplication: " << num1 * num2 << endl;
    cout << "Division: " << num1 / num2 << endl; // Be cautious of division by zero
    cout << "Modulus: " << num1 % num2 << endl; // Be cautious of division by zero

    return 0;
}
Compile and Run:
Compile the code using a C++ compiler and run the program. Input different values to observe how each arithmetic operator handles the numbers and produces results.

Conclusion:
Arithmetic operators in C++ are fundamental for performing basic mathematical calculations. The +, -, *, /, and % operators are essential tools for manipulating numeric data. By understanding these operators, programmers can efficiently handle arithmetic operations in their programs. The examples illustrate their practical application and reinforce their importance in everyday programming tasks.



