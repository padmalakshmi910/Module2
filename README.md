## Built-in Functions -Binary Conversion Using Built-in Functions in Python
## Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## Algorithm
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.
## Program
```
num = int(input())
binary = bin(num)
print("Binary value:", binary)
```
## Output
<img width="1261" height="322" alt="Screenshot 2026-06-01 133034" src="https://github.com/user-attachments/assets/ecd8e23e-5197-414c-b169-8a0ed3700ef2" />
## Result
Thus ,the program has been executed successfully.

## Functions in Python: Modulo Calculator
## Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## Algorithm
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.
## Program
```
def modulo_calculator(a, b):
    return a % b
num1 = int(input())
num2 = int(input())
result = modulo_calculator(num1, num2)
print("Remainder:", result)
```
## Output
<img width="1298" height="391" alt="Screenshot 2026-06-01 133821" src="https://github.com/user-attachments/assets/cee510f5-ef32-4bb0-b16a-048e88378e4f" />

## Result
Thus ,the program has been executed successfully.

## Lambda Function in Python: Addition of Two Numbers
## Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## Algorithm
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
## Program
```
add = lambda a, b: a + b
num1 = int(input())
num2 = int(input())
print("Sum =", add(num1, num2))
```
## Output
<img width="1281" height="295" alt="Screenshot 2026-06-01 134408" src="https://github.com/user-attachments/assets/f736ec7c-a5f2-41fc-b076-b6a45e8c040f" />


## Result
Thus ,the program has been executed successfully.

## Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## Algorithm
Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
## Program
```
n = int(input())
for i in range(n):
    num = 1
    for j in range(n - i - 1):
        print(" ", end="")
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()
```
## Output
<img width="1358" height="538" alt="Screenshot 2026-06-01 134806" src="https://github.com/user-attachments/assets/b89da2ca-2ee7-43ed-ae7c-e17b41bb2c0c" />
## Result
Thus ,the program has been executed successfully.

## Loops in Python: Palindrome Number Checker
## Aim
To write a Python program that checks whether a given number is a palindrome using loops.

## Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
## Program
```
num = int(input())
original = num
reverse = 0

while num > 0:
    digit = num % 10
    rev = rev * 10 + digit
    num = num // 10

if original == rev:
    print("Palindrome Number")
else:
    print("Not a Palindrome Number")
```
## Output
<img width="1417" height="640" alt="Screenshot 2026-06-01 135847" src="https://github.com/user-attachments/assets/c657ecf8-747e-4bdf-b130-c11e154751d6" />

## Result
Thus, the program has been executed successfully.

