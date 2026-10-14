# Modular Calculator - Version 2
# Improved with error handling and formatted output

def add_numbers(num1, num2):
    """Return the sum of two numbers."""
    return num1 + num2


def subtract_numbers(num1, num2):
    """Return the difference between two numbers."""
    return num1 - num2


def multiply_numbers(num1, num2):
    """Return the product of two numbers."""
    return num1 * num2


def divide_numbers(num1, num2):
    """Return the quotient if the divisor is not zero."""
    if num2 == 0:
        return "Error: Cannot divide by zero."
    return num1 / num2


try:
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    print("Choose Operation:")
    print("1 - Addition (+)")
    print("2 - Subtraction (-)")
    print("3 - Multiplication (*)")
    print("4 - Division (/)")

    choice = input("Enter choice: ")

    if choice == "1":
        result = add_numbers(num1, num2)
    elif choice == "2":
        result = subtract_numbers(num1, num2)
    elif choice == "3":
        result = multiply_numbers(num1, num2)
    elif choice == "4":
        result = divide_numbers(num1, num2)
    else:
        result = "Invalid operation choice."

    print(f"Result: {result}")

except ValueError:
    print("Error: Please enter valid numbers.")
