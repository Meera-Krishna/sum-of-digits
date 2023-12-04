# sum-of-digits
def sum_of_digits(number):
    # Convert the number to a string to iterate over its digits
    number_str = str(number)
    
    # Sum the digits using a loop
    digit_sum = 0
    for digit in number_str:
        digit_sum += int(digit)
    
    return digit_sum

# Example usage
input_number = 12345
result = sum_of_digits(input_number)

print(f"The sum of digits in {input_number} is: {result}")
