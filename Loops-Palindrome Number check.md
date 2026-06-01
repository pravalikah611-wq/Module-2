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

# Program to check palindrome number using loops

num = int(input("Enter a number: "))
temp = num
reverse = 0

while temp > 0:
    digit = temp % 10
    reverse = reverse * 10 + digit
    temp = temp // 10

if num == reverse:
    print("The number is a Palindrome.")
else:
    print("The number is not a Palindrome.")


<img width="1482" height="696" alt="image" src="https://github.com/user-attachments/assets/767034f6-b501-4327-a638-2104caba6b70" />

## Output:

<img width="1482" height="696" alt="image" src="https://github.com/user-attachments/assets/c35978b3-fb78-4191-a770-38a14ccda235" />

## Result;

The program successfully checks whether the given number is a palindrome using a loop and displays the correct result.

