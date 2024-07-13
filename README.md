# -even-or-odd
# Function to check if a number is even or odd
def check_even_odd(number):
    if number % 2 == 0:
        print(f"The number {number} is even.")
    else:
        print(f"The number {number} is odd.")

# Ask the user for a number
user_number = int(input("Please enter a number: "))

# Check if the number is even or odd
check_even_odd(user_number)
