**Name:** Asti Sojitra  
**Assignment:** Practical Assignment
  
# Logic Box  
  
## Project Description  
  
Logic Box is a Python console-based project called Pattern Generator and Number Analyzer. This project helps to practice Python programming concepts and logical problem-solving skills.  
  
## Features  
  
### Pattern Generator
- Generates a right-angled triangle pattern.  
- Takes the number of rows as input.  
- Uses nested loops to generate the pattern.  
  
**Example:**  
  
    *
    **
    ***
    ****
    *****

### Number Analyzer  
  
- Takes a starting number and ending number as input.  
- Checks whether each number is Odd or Even.  
- Calculates the sum of all numbers in the given range.  
  
**Example:**  
  
    Number 10 is Even
    Number 11 is Odd
    Number 12 is Even
    Number 13 is Odd
    Number 14 is Even
    Number 15 is Odd

    Sum of all numbers from 10 to 15 is: 75

## Menu-Driven System

The project provides a simple menu-driven system with three options:

    1. Generate a Pattern
    2. Analyze a Range of Numbers
    3. Exit

The program continuously displays the menu using a `while` loop until the user selects the Exit option.

## Program Working

When the user selects **Option 1**, the program asks for the number of rows and generates a right-angled triangle pattern using a `for` loop and `range()` function.

When the user selects **Option 2**, the program asks for the starting and ending numbers. It checks each number in the selected range using the modulo `%` operator and identifies whether the number is Odd or Even. It also calculates the total sum of all numbers.

When the user selects **Option 3**, the program exits using the `break` statement and displays a goodbye message.

If the user enters an invalid choice, the program displays an invalid choice message and allows the user to select an option again.

## Sample Output

    Logic Box!

    Select an option:
    1. Generate a Pattern
    2. Analyze a Range of Numbers
    3. Exit

    Enter your choice: 1
    Enter the number of rows for the pattern: 4

    Pattern:
    *
    **
    ***
    ****

After selecting option 2:

    Enter your choice: 2

    Enter the start of the range: 1
    Enter the end of the range: 3

    Number 1 is Odd
    Number 2 is Even
    Number 3 is Odd

    Sum of all numbers from 1 to 3 is: 6

After selecting option 3:

    Enter your choice: 3
    Exiting the program. Goodbye!

## Python Concepts Used

- Variables
- User Input
- `print()` function
- `input()` function
- `int()` type conversion
- `if`, `elif`, and `else` statements
- `for` loop
- `while` loop
- Nested loops
- `range()` function
- Modulo `%` operator
- Arithmetic operations
- `break` statement
- Menu-driven programming
- Odd and Even number checking
- Basic logical problem solving

## Learning Outcome

This project helped me understand basic Python programming concepts and improve my logical problem-solving skills. I practiced loops, conditional statements, user input, arithmetic operations, Odd and Even number checking, pattern generation, and menu-driven programming.

## Tools Used

- Python
- Visual Studio Code
- Python Terminal

## Project Type

**Console-Based Python Application**

## Conclusion

Logic Box is a simple Python console-based practical project that combines Pattern Generation and Number Analysis. It provides practical experience with Python loops, conditional statements, operators, user input, and menu-driven programming. This project helped me strengthen my Python fundamentals and logical thinking skills.

## Author

**Asti Sojitra**

**Practical Assignment - Logic Box**
