README.md
Most security issues start with bad input.

This example shows how small checks
prevent bigger problems later.
Code (validate_input.py)
age = input("Enter age: ")

if age.isdigit():
    print("Valid age:", age)
else:
    print("Invalid input detected")
Commit message:
