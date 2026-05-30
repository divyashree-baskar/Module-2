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
```
a=int(input())
def fact(x):
    f=1
    for i in range(1,x+1):
        f*=i
    return f
for i in range(a):
    for j in range(i+1):
        a=fact(i)/((fact(j))*fact(i-j))
        print(int(a),end=" ")
    print()
        
```
## Sample Output
<img width="805" height="537" alt="image" src="https://github.com/user-attachments/assets/097c10a8-0666-48b8-a146-979d8cf2b7b1" />

## Result
Thus the program has been successfully executed.
