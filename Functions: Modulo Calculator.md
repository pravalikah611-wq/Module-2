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

# Function to find modulo of two numbers

def find_modulo(a, b):
    return a % b

# Taking input from user
x = int(input("Enter first number: "))
y = int(input("Enter second number: "))

# Calling the function
result = find_modulo(x, y)

print("Modulo result:", result)

<img width="1515" height="641" alt="image" src="https://github.com/user-attachments/assets/3a77f325-0919-4cc1-8830-1a5d3db50e97" />


## Output:

<img width="1515" height="641" alt="image" src="https://github.com/user-attachments/assets/3a77f325-0919-4cc1-8830-1a5d3db50e97" />

## Result:

The program successfully defines a function that returns the modulo (remainder) of two numbers using the % operator and displays the correct result.
