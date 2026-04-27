# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```py

def fun(n):
    if n > 0: fun(n-2); print(n, end=" ")

x = int(input())
fun(x if x % 2 == 0 else x - 1)

```
## OUTPUT

<img width="948" height="247" alt="446831269-0d26f5fe-9e30-4e5c-a175-c130f693849c" src="https://github.com/user-attachments/assets/616d1f4e-e358-4bf6-8b64-bd9d413bda05" />

## RESULT
Thus, the program is executed successfully.
