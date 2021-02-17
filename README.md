# encircle
# This is a test-file.

Write a command line program that acts as a simple calculator: it takes a single argument as an expression and prints out the integer result of evaluating it.

Assumptions
A list of assumptions that were allowed to make:

A function call is always delimited by parenthesis ( and ).

Since numbers are specified by digits only, you don't have to deal with inputting negative numbers.

Depending on your choice of language, you may have to pick a data type to represent your integers and calculations. Pick something that gives you at least 32 bits. None of the calculations will deal with numbers larger than that and you won't be penalized for not dealing with overflow.

You can be pretty lax about error handling. Throwing an exception when in an invalid state is fine.

The tested examples will always be well formed. That means that:

Parenthesis will always be balanced.
Only the add and multiply functions will be called.
There will always be a single space between the function arguments

To execute, follow the interface as in the problem statement: ./calc.py "(add 12 12)"

Assuming the program is implemented in Python, invocations should look like:

$ ./calc.py 123
-> 123

$ ./calc.py "(add 12 12)"
-> 24


