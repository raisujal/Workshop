1.
# The perimeter of a rectangle with length 9 & width 7
perimeter = 2 * (9 + 7)
print('The perimeter is:', perimeter)

# Your name stored as a variable
name = 'Sujal Rai'
print('Your name stored as a variable is:', name)

# Python is great, it's wild!
print('Python is great, it\'s wild!')

# The difference between Beth's age (57) and Tom's (34)
beth_age = 57
tom_age = 34
age_diff = beth_age - tom_age
print('The difference between Beth age and Tom is:', age_diff)

# 2 to the 10th power
power_10 = 2 ** 10
print('2 to the 10th power is:', power_10)

# 7 factorial minus 5 factorial
import math

def factorial(n):
    return math.factorial(n)

seven_fact = factorial (7)
five_fact = factorial (5)
x = seven_fact - five_fact
print('7 factorial minus 5 factorial is:', x)

# Your forename multiplied by 5
multiplied_name = 'Sujal' * 5
print('Your forename multiplied by 5 is:', multiplied_name)

# Your name left justified 15 spaces
name = 'Sujal Rai'
left_justified_name = name.ljust (15)
print('Your name left justified 15 spaces is:', left_justified_name)

# PI to 5 decimal places
import math

pi_to_5_decimal_places = round(math.pi, 5)
print('PI to 5 decimal places is:', pi_to_5_decimal_places)

# 200 modulus 12
modulus_value = 200 % 12
print('200 modulus 12 is:', modulus_value)

# The Unicode encoding for your name
name = 'Sujal Rai'
unicode_name = name.encode('unicode-escape')
print('Unicode encoding for your name is:', unicode_name)

# 7.2 as an integer value
integer_value = int(7.2)
print('7.2 as an integer value is:', integer_value)







Part 2
2.

first_number = int(input('Enter the first integer value: '))
second_number = int(input('Enter the second integer value: '))

result = first_number / second_number

print(f'The result is: {result:.2f}')



3.
first_number = float(input("Enter the first floating-point value: "))

second_number = float(input("Enter the second floating-point value: "))

result = first_number / second_number

print(f"The result is: {result:.2f}")




4.

first_number = float(input("Enter the first floating-point value: "))

second_number = float(input("Enter the second floating-point value: "))

result = first_number / second_number

print(f"The result is: {result:.2e}")

5.

utf8_value = int(input("Enter a UTF-8 value between 32 and 126: "))

if 32 <= utf8_value <= 126:
print(f"The corresponding character for UTF-8 value {utf8_value} is: {chr(utf8_value)}")

else:
print(f"Error: The UTF-8 value {utf8_value} is outside the valid range of 32 to 126.")

Part 3

6.
utf8_value = int(input("Enter a UTF-8 value between 32 and 126: "))

if 32 <= utf8_value <= 126:
    print(f"The corresponding character for UTF-8 value {utf8_value} is: {chr(utf8_value)}")

else:
    print("The UTF-8 value is outside the valid range of 32 to 126.")


7.
def squared(n):
    return n * n

result = squared(5)
print(result)


8.
def divide_two_numbers():
    num1 = int(input("Enter the first number: "))
    num2 = int(input("Enter the second number: "))
    result = num1 / num2
    print(f"The result is {result:.2f}")

divide_two_numbers()
# Workshop
