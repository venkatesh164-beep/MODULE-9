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
n = int(input("Enter the number of students: "))<br>
students = []<br>

for _ in range(n):<br>
    name = input("Enter student's name: ")<br>
    grade = float(input("Enter student's grade: "))<br>
    students.append([name, grade])<br>

grades = sorted(set([student[1] for student in students]))<br>

second_lowest_grade = grades[1]<br>


second_lowest_students = sorted([student[0] for student in students if student[1] == second_lowest_grade])<br>

for name in second_lowest_students:<br>
    print(name)<br>

## Output
<img width="346" height="411" alt="image" src="https://github.com/user-attachments/assets/6d55fa84-77eb-4d68-8cf8-dc759336fb27" />

## Result

Thus,the program is executed successfully
