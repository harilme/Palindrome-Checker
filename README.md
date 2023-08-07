# Palindrome-Checker

def is_palindrome(s):
    s = s.lower()  # Convert the string to lowercase for case-insensitive comparison
    s = s.replace(" ", "")  # Remove spaces from the string

    return s == s[::-1]  # Compare the string with its reverse

# Get input from the user
input_string = input("Enter a string: ")

# Check if the input string is a palindrome
result = is_palindrome(input_string)

# Print the result
print("Is the input string a palindrome?", result)

