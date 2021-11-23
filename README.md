# repo1
about python programs
# Simple Python program to Add Two Numbers

number1 = input(" Please Enter the First Number: ")
number2 = input(" Please Enter the second number: ")

# Using arithmetic + Operator to add two numbers
sum = float(number1) + float(number2)
print('The sum of {0} and {1} is {2}'.format(number1, number2, sum))

 Please Enter the First Number: 22
 Please Enter the second number: 44
The sum of 22 and 44 is 66.0

# Python Program to Calculate Cube of a Number

number = float(input(" Please Enter any numeric Value : "))

cube = number * number * number

print("The Cube of a Given Number {0}  = {1}".format(number, cube))

Please Enter any numeric Value : 5
The Cube of a Given Number 5.0  = 125.0

# Python Program to check if a Number is Odd or Even

number = int(input(" Please Enter any Integer Value : "))

if(number % 2 == 0):
    print("{0} is an Even Number".format(number))
else:
    print("{0} is an Odd Number".format(number))
    number = int(input(" Please Enter any Integer Value : "))
    
    Please Enter any Integer Value : 9
9 is an Odd Number

Please Enter any Integer Value : 28
28 is an Even Number
