# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

---

## 💻 PROGRAM:
def read_matrix(n):<br>
    matrix=[[0]*n for row in range(n)]<br>
    for i in range(n):<br>
        lines=list(map(int,input().split()))<br>
        for j in range(n):<br>
            matrix[i][j]=lines[j]<br>
    return matrix<br>
def print_matrix(M):<br>
    print("Matrix:")<br>
    for i in range(len(M)):<br>
        for j in range(len(M[0])):<br>
            if(i>j or i==j):<br>
                print(M[i][j],end=" ")<br>
            else:<br>
                print(0,end=" ")<br>
        print()
## OUTPUT:
<img width="538" height="332" alt="image" src="https://github.com/user-attachments/assets/08230d4f-17d7-4bed-94cb-65290cd3b409" />

## RESULT:
Thus the output is verified.
