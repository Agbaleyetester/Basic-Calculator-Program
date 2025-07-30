# Basic-Calculator-Program
Introduction to Python assignment
## A simple Python program that ask users to input two numbers and a mathematical operation (addition, substraction, multiplication, or division),
peform the operation based on the user's input and print the result.

##CODE
Num1 = float(input("Enter the first number: "))
Num2 = float(input("Enter the second number: "))
Operation = input("Enter the operation (+, -, *, /): ")

Result = {
          "+": Num1 + Num2,
          "-": Num1 - Num2,
          "*": Num1 * Num2,
          "/": Num1 / Num2 if Num2 != 0 else "Error: Division by Zero!"}

print(f"{Num1} {Operation} {Num2} = {Result.get(Operation, 'Invalid operation')}")
