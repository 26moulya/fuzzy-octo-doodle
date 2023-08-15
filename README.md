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









