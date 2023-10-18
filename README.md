# Recursion

THEORY

Recursion is the technique of making a function call itself. This technique provides a way to break complicated problems down into simple problems which are easier to solve.

Recursion may be a bit difficult to understand. The best way to figure out how it works is to experiment with it.

Recursion Example Adding two numbers together is easy to do, but adding a range of numbers is more complicated. In the following example, recursion is used to add a range of numbers together by breaking it down into the simple task of adding two numbers.

ALGORITHM

Algorithm: Factorial Calculation
Input: An integer 'n' for which you want to calculate the factorial. Output: The factorial of 'n'.

Start with a function named 'factorial' that takes an integer 'n' as its argument.
Inside the 'factorial' function: a. Check the base case: If 'n' is 0 or 1, return 1 because the factorial of 0 and 1 is 1. b. If 'n' is greater than 1, calculate the factorial recursively as follows:
Multiply 'n' by the result of the 'factorial' function with argument 'n - 1'.
Return this result.
In the 'main' function: a. Declare an integer 'num' to store the input number for which you want to calculate the factorial. b. Ask the user to input the value of 'num'. c. Call the 'factorial' function with 'num' as the argument to compute the factorial. d. Display the result as the factorial of 'num'.
Algorithm: Sum of Integers from 1 to n
Algorithm: Sum of Integers from 1 to n Using Recursive Function

Input: A positive integer 'n'. Output: The sum of all integers from 1 to 'n'.

Initialize a recursive function 'sumOfIntegers' that takes an integer 'n' as its argument.
In the 'sumOfIntegers' function: a. Check the base case: If 'n' is 1, return 1 because the sum of integers from 1 to 1 is 1. b. If 'n' is greater than 1, calculate the sum recursively as follows:
Return 'n' plus the result of the 'sumOfIntegers' function with argument 'n - 1'.
In the 'main' function: a. Declare an integer variable 'n' to store the input value for which you want to calculate the sum. b. Ask the user to input the value of 'n'. c. Call the 'sumOfIntegers' function with 'n' as the argument to compute the sum. d. Display the result as the sum of integers from 1 to 'n'.
Algorithm: Print String in Reverse Using Recursive Function
Input: A string 'str' and the length of the string 'n'. Output: Print the characters of 'str' in reverse order.

Initialize a recursive function 'printReverseString' that takes two arguments: 'str' and 'n'.
In the 'printReverseString' function: a. Check the base case: If 'n' is 0 (the string is empty), return. b. Print the last character of 'str' (str[n-1]). c. Call the 'printReverseString' function recursively with 'str' excluding the last character (str[0 to n-2]) and 'n-1' as arguments.
In the 'main' function: a. Declare a character array 'str' to store the input string. b. Read the input string into 'str'. c. Calculate the length of the input string and store it in 'n'. d. Call the 'printReverseString' function with 'str' and 'n' as arguments to print the string in reverse order

OUTPUT

Factorial code:

Enter a non-negative integer: 3

Factorial of 3 is 6

Sum of Integers code

Enter a positive integer 'n': 2

The sum of integers from 1 to 2 is: 3

Reverse a string

Enter a string: Symbiosis Institute Of Technology

String in reverse: ygolonhceT fO etutitsnI sisoibmyS
