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
def wrap(string, max_width):<br>
    wrapped_lines = []<br>
    for i in range(0, len(string), max_width):<br>
        wrapped_lines.append(string[i:i+max_width])<br>
    return '\n'.join(wrapped_lines)<br>

text = input("Enter a long string: ")<br>
width = int(input("Enter max width: "))<br>
print("\nWrapped Text:\n")<br>
print(wrap(text, width))

## Sample Output
<img width="738" height="400" alt="image" src="https://github.com/user-attachments/assets/af0e95a2-459c-468a-8520-ddd15152fde7" />

## Result
Program is verified successfully.

