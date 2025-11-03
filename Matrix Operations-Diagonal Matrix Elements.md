# Matrix Operations-Diagonal Matrix Elements Printer 🧮

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

## 📌 Aim

To write a Python program that prints only the diagonal elements of a given matrix.

## 🧠 Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

## 🖥️ Program
rows=int(input())<br>
columns=int(input())<br>
matrix=[[0]*columns for row in range(rows)]<br>
for i in range(rows):<br>
    lines=list(map(int, input().split()))<br>
    for j in range(columns):<br>
        matrix[i][j]=lines[j]<br>
print(matrix)<br>
for i in range(rows):<br>
    for j in range(columns):<br>
        if(i==j):<br>
            print(matrix[i][j],end=" ")<br>
        else:<br>
            print(' ',end=" ")<br>
    print()

### Output:
<img width="776" height="324" alt="image" src="https://github.com/user-attachments/assets/209c4245-a4d2-4c19-8b30-d2a9ab624f1f" />

## Result
Thus the output is verified.
