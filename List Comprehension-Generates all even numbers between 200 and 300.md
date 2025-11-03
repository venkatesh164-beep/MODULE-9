# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
class Generate:<br>
    def __init__(self, first,d,last):<br>
        self.first = first<br>
        self.d = d<br>
        self.last=<br>
    def Ap_generate(self):<br>
        L=[i for i in range(self.first,self.last+1,self.d)]<br>
        return L<br>
Series = Generate(200,2,301)<br>
print(Series.Ap_generate())

## OUTPUT:
<img width="1225" height="174" alt="image" src="https://github.com/user-attachments/assets/6f9d1c4e-b39d-4a18-a252-2770319ae0b8" />

## RESULT:
Thus the output is verified
