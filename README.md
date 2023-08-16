Code for Beginners Python
## To print a statement
print("Hello  World!")

# User gives the input
  a = int(input("enter first number:"))
b = int(input("enter second number:"))
result = print(a+b)

# Two number intialized
num1 = 2
num2 = 6
# Add two numbers
sum = num1 + num2
# print 
print(sum)

# intialize
i = 1
while i < 6:
  print(i)
  i += 1
  
  # switch case is used
  a=int(input("enter First number:"))
b=int(input("enter Second number:"))
def add(a,b):
    print(a+b)
def sub(a,b):
    print(a-b)
def mul(a,b):
    print(a*b)
def div(a,b):
    print(a/b)
print("\n 1.add\n 2.sub\n 3 mul\n 4 div\n")
choice=int(input("enter your choice"))
if choice==1:
    add(a,b)
elif choice==2:
    sub(a,b)
elif choice==3:
    mul(a,b)
elif choice==4:
    div(a,b)
elif choice==5:
    print("exit")
else:
    print("invalid choice")
    
# Add two numbers
x=10
y=30
print(x+y)

## swap
def swapList(newList):
    size = len(newList)
     
    # Swapping
    temp = newList[0]
    newList[0] = newList[size - 1]
    newList[size - 1] = temp
     
    return newList
     
# Driver code
newList = [12 ,35, 9, 56, 24]
 
print(swapList(newList))
 ##usage of star
 list = [1, 2, 3, 4]
 
a, *b, c = list
 
print(a)
print(b)
print(c)
## palindrome

string = 'moulya'
half = int(len(string) / 2)
 
 
first_str = string[:half]
second_str = string[half:]
 
 
# symmetric
if first_str == second_str:
    print(string, 'string is symmetrical')
else:
    print(string, 'string is not symmetrical')
 
# palindrome
if first_str == second_str[::-1]:  # ''.join(reversed(second_str)) [slower]
    print(string, 'string is palindrome')
else:
    print(string, 'string is not palindrome'

    
  ## digit pattern

def pattern(n): 
  
    # traverse through the elements 
    # in n assuming it as a string 
    for i in n: 
  
        # print | for every line 
        print("|", end = "") 
  
        # print i number of * s in 
        # each line 
        print("*" * int(i)) 
  
# get the input as string         
n = "41325"
pattern(n)



Beginners level
1. Print "Hello, World!":

2. Calculate the Area of a Rectangle:

def calculate_rectangle_area(length, width):
    area = length * width
    return area

length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))
area = calculate_rectangle_area(length, width)
print("The area of the rectangle is:", area)

3. Check if a Number is Even or Odd:

def check_even_odd(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"

number = int(input("Enter a number: "))
result = check_even_odd(number)
print(f"The number {number} is {result}.")

4. Convert Temperatures between Fahrenheit and Celsius:


def fahrenheit_to_celsius(fahrenheit):
    celsius = (fahrenheit - 32) * 5 / 9
    return celsius

def celsius_to_fahrenheit(celsius):
    fahrenheit = (celsius * 9 / 5) + 32
    return fahrenheit

temperature = float(input("Enter temperature: "))
unit = input("Enter unit (F or C): ")

if unit.upper() == "F":
    celsius_temp = fahrenheit_to_celsius(temperature)
    print(f"{temperature}°F is {celsius_temp:.2f}°C")
elif unit.upper() == "C":
    fahrenheit_temp = celsius_to_fahrenheit(temperature)
    print(f"{temperature}°C is {fahrenheit_temp:.2f}°F")
else:
    print("Invalid unit.")
    
5. Generate Fibonacci Sequence:


def generate_fibonacci(n):
    fib_sequence = [0, 1]
    for i in range(2, n):
        next_number = fib_sequence[-1] + fib_sequence[-2]
        fib_sequence.append(next_number)
    return fib_sequence

n = int(input("Enter the number of terms: "))
fibonacci_sequence = generate_fibonacci(n)
print("Fibonacci Sequence:", fibonacci_sequence)

6. Calculate Factorial:


def calculate_factorial(n):
    factorial = 1
    for i in range(1, n + 1):
        factorial *= i
    return factorial

n = int(input("Enter a number: "))
factorial = calculate_factorial(n)
print(f"The factorial of {n} is {factorial}.")

7. Simple Calculator:

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == '1':
    print(num1, "+", num2, "=", add(num1, num2))
elif choice == '2':
    print(num1, "-", num2, "=", subtract(num1, num2))
elif choice == '3':
    print(num1, "*", num2, "=", multiply(num1, num2))
elif choice == '4':
    print(num1, "/", num2, "=", divide(num1, num2))
else:
    print("Invalid input")








