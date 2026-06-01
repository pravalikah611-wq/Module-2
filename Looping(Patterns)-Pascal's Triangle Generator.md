# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
# Program to generate Pascal's Triangle

rows = int(input("Enter number of rows: "))

for i in range(rows):
    num = 1
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()

<img width="1489" height="526" alt="image" src="https://github.com/user-attachments/assets/780349fc-4746-4d43-af7e-6ff9977e23ad" />



## Sample Output:

<img width="1489" height="526" alt="image" src="https://github.com/user-attachments/assets/6e2d908d-2cc6-4d60-a4bf-db5f2781aea7" />


## Result:
The program successfully generates Pascal’s Triangle based on the number of rows entered by the user and displays the correct pattern.


