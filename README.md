# Rolle_ModularCalculator
def add(a, b):
    return a + b
def subtract(a, b):
    return a - b
def multiply(a, b):
    return a * b
def divide(a, b):
    if b == 0:
        return "Cannot divide by zero!"
    return a / b

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("1 - Add")
print("2 - Subtract")
print("3 - Multiply")
print("4 - Divide")

choice = input("Choose an operation: ")

if choice == "1":
    answer = add(num1, num2)
elif choice == "2":
    answer = subtract(num1, num2)
elif choice == "3":
    answer = multiply(num1, num2)
elif choice == "4":
    answer = divide(num1, num2)
else:
    answer = "Invalid choice!"

print("Answer:", answer)
