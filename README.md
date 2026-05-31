# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
b=bin(a)
print(b)
```
## Output

<img width="1600" height="842" alt="WhatsApp Image 2026-05-31 at 7 36 56 PM" src="https://github.com/user-attachments/assets/2dc81284-6cf8-48fd-9637-8edb3beb1a3c" />

## Result
Thus , the program is executed sucessfully

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(a % b)

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

result(a, b)
```
## Output
<img width="1376" height="226" alt="image" src="https://github.com/user-attachments/assets/7345f3dd-4852-4de8-8644-a28099bcf0ad" />

## Result
The program was executed successfully and printed the modulo (remainder) of the two numbers using the % operator.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input("Enter the first number: "))
b=int(input("Enter the second number: "))
f = lambda a , b : a + b
print("The sum is : ",f(a,b))
```

## Output
<img width="1600" height="846" alt="WhatsApp Image 2026-05-31 at 7 38 15 PM" src="https://github.com/user-attachments/assets/119801ef-b3b1-4312-b6f9-91b7ddf9cfc4" />

## Result
Thus ,the program is executed successfully

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
from math import factorial
n = int(input("Enter the number of rows: "))
for i in range(n):
    print(' ' * (n - i - 1), end='')
    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=' ')
    print()
```
## Sample Output
<img width="1600" height="856" alt="WhatsApp Image 2026-05-31 at 7 38 55 PM" src="https://github.com/user-attachments/assets/2b558824-5db2-4755-909b-80bd0642fab1" />

## Result
Thus ,the program is executed successfully

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
n = int(input("Enter a number: "))
temp = n
rev = 0
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev == n:
    print(n, "is a palindrome")
else:
    print(n, "is not a palindrome")
```

## Output
<img width="1600" height="844" alt="WhatsApp Image 2026-05-31 at 7 39 13 PM" src="https://github.com/user-attachments/assets/be19b28d-17a6-4c83-ba82-3b5a20db67ef" />

## Result
Thus,the program is executed successfully
