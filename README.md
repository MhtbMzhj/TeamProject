def calculate_product(num1, num2):
    return num1 * num2

def calculate_square(num):
    return num * num

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

product_result = calculate_product(num1, num2)

print(f"The product of {num1} and {num2} is: {product_result}")

num = int(input("Enter a number to calculate its square: "))

square_result = calculate_square(num)

print(f"The square of {num} is: {square_result}")
