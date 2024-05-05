# Python Control Structure & Operators


## Introduction and Recap
- Recap the previous session, highlighting key points such as setting up Python, basic syntax, and running simple Python programs.
- Outline the agenda for the current session, focusing on math operators and control structures.

## Math Operators in Python
- Discuss various types of operators in Python, including:
  - **Arithmetic Operators**: `+`, `-`, `*`, `/`, `//` (floor division), `%` (modulus), `**` (exponentiation)
```
  python
  # Basic arithmetic operations
  a = 10
  b = 3
  print("Addition:", a + b)
  print("Subtraction:", a - b)
  print("Multiplication:", a * b)
  print("Division:", a / b)
  print("Floor Division:", a // b)
  print("Modulus:", a % b)
  print("Exponentiation:", a ** b)
```

  - **Comparison Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
```
# Comparison operators
x = 5
y = 10
print("x equals y:", x == y)
print("x not equals y:", x != y)
print("x is greater than y:", x > y)
  - **Logical Operators**: `and`, `or`, `not`
```
- **Operators**: `and`, `or`, `not`
```
# Logical operators
is_raining = True
is_weekend = False
print("Go outside:", is_raining == False and is_weekend == True)
print("Stay indoors:", is_raining or not is_weekend)
```


## Control Structures in Python
- Introduce control structures, focusing on:
  - **If-Else Statements**
```
# If-else structure
age = 18
if age < 13:
    print("Child")
elif age < 20:
    print("Teenager")
else:
    print("Adult")
```

  - **While Loops**
```
# While loop
count = 0
while count < 5:
    print("Count is", count)
    count += 1
```
  - **For Loops**
```
# For loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print("Fruit:", fruit)
```

## Interactive Exercises and Programs
- Exercise 1: Write a program that takes two numbers as input and performs various arithmetic operations on them.

- Exercise 2: Create a program that asks for the user's age and outputs whether they are a child, teenager, or adult based on age ranges.

- Exercise 3: Write a program that uses a loop to print numbers from 1 to 10.
