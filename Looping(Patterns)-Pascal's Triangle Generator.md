# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---
)

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
~~~
import math
rows = int(input("Enter the number of rows: "))

for n in range(rows):
    
    print(' ' * (rows - n), end='')

    
    for k in range(n + 1):
        value = math.comb(n, k)  # math.comb() directly computes combinations
        print(value, end=' ')
    
    
    print()
~~~

## Sample Output
![446127937-22798bfe-2b8c-4702-a7d6-887fb6a7ec72](https://github.com/user-attachments/assets/44585dbd-59a9-4e1c-8a91-31bb90d2020e)

## Result
Thus the program executed successfully.
