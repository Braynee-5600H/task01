# task01
simple calculator
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Error: Division by zero"

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
op = input("Enter operation (+, -, *, /): ")


if op == "+":
    result = add(num1, num2)
elif op == "-":
    result = subtract(num1, num2)
elif op== "*":
    result = multiply(num1, num2)
elif op == "/":
    result = divide(num1, num2)
else:
    result = "Invalid operation"


print(f"Result:  “,result)


