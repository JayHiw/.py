# .py
notes for python and projects.(TRACKING DOWN EVERYTHING). 

# MY PYTHON NOTES!!


This repository contains my daily learning notes and small experiments in Python.

## Day 1 – Getting Started
- Installed Python
- Learned print()
- Understood variables

## Day 2 – Data Types
- int, float, string
- type() function
  - also
 
What I focused on today

Strengthened core Python fundamentals

Practiced logical thinking & problem decomposition

Understood how small decisions affect program flow

Improved code readability and structure

Continued building the habit of daily learning & tracking

 Key Learnings

Writing code is easy, writing understandable code is a skill

Logic > syntax

Clean structure today saves debugging time tomorrow

Consistency compounds faster than motivation

Small Practice Snippet
# Simple logic practice: even or odd checker

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
### Mini Experiment – Understanding Types
```python
a = 10
b = 3.14
c = "Python"
d = True

print(a, type(a))
print(b, type(b))
print(c, type(c))
print(d, type(d))

### Day 3  – Python & Learning

- Continued strengthening Python fundamentals
- Practiced problem-solving and logical thinking
- Focused on writing clean and readable code...


Day 4 – Control Flow (Decision Making)
- Learned conditional statements
- if, elif, else
- Comparison operators
- Logical operators (and, or, not)

### Mini Experiment – Conditional Logic
```python
age = 19

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
for i in range(1, 6):
    print("Iteration:", i)

count = 1
while count <= 5:
    print("Count:", count)
    count += 1




Program to Find Sum of Two Numbers
Aim

To add two numbers entered by the user.

Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b
print("Sum =", sum)

Output
Enter first number: 10
Enter second number: 20
Sum = 30

🔹 4. Program to Check Even or Odd
Aim

To check whether a number is even or odd.

Code
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

Output
Enter a number: 7
Odd number

🔹 5. Program to Find Largest of Three Numbers
Aim

To find the largest of three numbers.

Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b and a > c:
    print("Largest number is", a)
elif b > c:
    print("Largest number is", b)
else:
    print("Largest number is", c)

Output
Largest number is 25
