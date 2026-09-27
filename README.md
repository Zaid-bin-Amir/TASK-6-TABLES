# TASK-6-TABLES
def print_multiplication_table(number, limit):
    print(f"Multiplication Table for {number} (up to {limit}):")
    for i in range(1, limit + 1):
        print(f"{number} x {i} = {number * i}")
number = int(input("Enter a number: "))
limit = int(input("Enter the limit: "))

print_multiplication_table(number, limit)
