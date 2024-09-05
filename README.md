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
OUTPUT:
1.Arithmetic operations
![Screenshot 2024-09-05 153630](https://github.com/user-attachments/assets/5c2d1f41-783b-4659-b6ba-9a9f4fb56374)

2.Comparison operators
![Screenshot 2024-09-05 153637](https://github.com/user-attachments/assets/2da2ade1-2ded-415e-9593-c414b3080ac0)

3.Comparison operator with true and false:
![Screenshot 2024-09-05 153646](https://github.com/user-attachments/assets/3bab1814-17bf-4a28-8ec0-bfe7ca4212a0)

4.Logical operator with true and false:
![Screenshot 2024-09-05 153653](https://github.com/user-attachments/assets/a3c302e7-fe7b-47dc-ab6f-9e89962c799d)

5.Logical operator:
![Screenshot 2024-09-05 153700](https://github.com/user-attachments/assets/585c1845-783a-4c99-b070-45a0af3201b0)

Conclusion:
Arithmetic operators in C++ are fundamental for performing basic mathematical calculations. The +, -, *, /, and % operators are essential tools for manipulating numeric data. By understanding these operators, programmers can efficiently handle arithmetic operations in their programs. The examples illustrate their practical application and reinforce their importance in everyday programming tasks.



