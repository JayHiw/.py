## Purpose of This Repo

###  Day 1 — Getting Started
- [x] Installed Python
- [x] Learned `print()`
- [x] Understood variables

---

###  Day 2 — Data Types
- [x] `int`
- [x] `float`
- [x] `str`
- [x] `bool`
- [x] Used `type()` function

#### Mini Experiment — Understanding Types
```python
a = 10
b = 3.14
c = "Python"
d = True

print(a, type(a))
print(b, type(b))
print(c, type(c))
print(d, type(d))


 Conditional statements (if, elif, else)

 Comparison operators

 Logical operators (and, or, not)

 for loop

 while loop

Mini Experiment — Conditional Logic
age = 19

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
Loop Practice
for i in range(1, 6):
    print("Iteration:", i)

count = 1
while count <= 5:
    print("Count:", count)
    count += 1




    2️⃣ Program to Check Even or Odd

Aim:
To check whether a number is even or odd.

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")




"""
Assignment No. 2
Subject: Python Programming
Topic: Control Statements and Loops
"""

# -------------------------------------------------
# 1. Using if statement
# Write a Python program to add two numbers only if both numbers are positive.
# -------------------------------------------------

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if num1 > 0 and num2 > 0:
    print("Sum =", num1 + num2)


# -------------------------------------------------
# 2. Using if–else statement
# Write a Python program to find the maximum of two numbers using an if–else control structure.
# -------------------------------------------------

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if a > b:
    print("Maximum number is:", a)
else:
    print("Maximum number is:", b)


# -------------------------------------------------
# 3. Using for loop
# Write a Python program to compute the factorial of a given number using a for loop.
# -------------------------------------------------

num = int(input("Enter a number: "))
factorial = 1

for i in range(1, num + 1):
    factorial *= i

print("Factorial of", num, "is", factorial)


# -------------------------------------------------
# 4. Using if–elif–else statement
# Write a Python program to calculate Simple Interest, where different interest rates
# are applied using if–elif–else based on the time period.
# -------------------------------------------------

p = float(input("Enter principal amount: "))
t = int(input("Enter time period (in years): "))

if t <= 2:
    r = 5
elif t <= 5:
    r = 7
else:
    r = 10

si = (p * t * r) / 100
print("Simple Interest =", si)


# -------------------------------------------------
# 5. Using while loop and if condition
# Write a Python program to check whether a given number is an Armstrong number.
# -------------------------------------------------

number = int(input("Enter a number: "))
temp = number
sum = 0

while temp > 0:
    digit = temp % 
