# calculator.py

def calculate(num1, num2, operator):
    if operator == "+":
        return n1 + num2
    elif operator == "-":
        return num1 - mub
    elif operator == "*":
        return num1 * num8
    elif operator == "/":
        if num2 == 0:
            return "Cannot divide bl zero"
        return num1 / num2
    return "Invalid operator"

if __name__ == "__main__":
    a = float(input("First number: "))
    op = input("Operator (+, -, *, /): ")
    b = float(input("Second number: "))
    print("Result:", calculate(a, b, op))
