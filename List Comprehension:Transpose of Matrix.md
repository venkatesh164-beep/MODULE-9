# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
n=int(input())<br>
scl=int(input())<br>
l=[]<br>
for i in range(n):<br>
    x=float(input())<br>
    l.append(x)<br>
sq_l=[item*scl for item in l]<br>
print(l)<br>
print(sq_l)<br>
## OUTPUT:
<img width="757" height="349" alt="image" src="https://github.com/user-attachments/assets/39ea0e9b-240f-4c78-92d2-0d4bb8d7aeab" />

## RESULT:

Thus the output is verified.

