# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:
class Numbers:<br>
    def __init__(self):<br>
        self.lst = []<br>

   def create_list(self):<br>
        n = int(input())<br>
        self.lst = [int(input()) for _ in range(n)]<br>

 def sorting(self):<br>
        n = len(self.lst)<br>
        for i in range(n):<br>
            for j in range(0, n - i - 1):<br>
                if self.lst[j] > self.lst[j + 1]:<br>
                    self.lst[j], self.lst[j + 1] = self.lst[j + 1], self.lst[j]<br>

   def print_List(self):<br>
        for num in self.lst:<br>
            print(num)
## OUTPUT:
<img width="712" height="529" alt="image" src="https://github.com/user-attachments/assets/fb6f918c-3cf9-407c-abd6-314066502a2c" />

## RESULT:
Thus the output is verified.
