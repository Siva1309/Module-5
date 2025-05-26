# Exp.No:23  
## Multiple Inheritance

---

### AIM  
To write a Python program using multiple inheritance to get a student’s name, attendance, and ID (grade), and determine if the student is eligible for placement based on their grade.

---

### ALGORITHM

Start the program.

Define class A:

In the constructor __init__(), accept input for:

n: Student's name

a: Student's attendance

i: Student's ID (grade)

Define class B inheriting from A:

Define disp1() to print the name and attendance.

Define class C inheriting from A:

Define disp2() to check if grade (i) is greater than 90:

If yes, print “Eligible for Placement”.

Else, print “Not Eligible for Placement”.

Define class D that inherits from both B and C (multiple inheritance).

Create an object o of class D.

Call disp1() to display name and attendance.

Call disp2() to check placement eligibility.

End the program.

---

### PROGRAM

```
class A:
    def __init__(self):
        self.n=input()
        self.a=int(input())
        self.i=int(input())
class B(A):
    def disp1(self):
        print(self.n)
        print(self.a)
class C(A):
    def disp2(self):
        if(self.i>90):
            print("Eligible for Placement")
        else:
            print("Not Eligible for Placement")
class D(B,C):
    pass
o=D()
o.disp1()
o.disp2()
```

### OUTPUT
![Screenshot (245)](https://github.com/user-attachments/assets/aa77c616-3c5f-4e1d-9464-76763c4fd43b)


### RESULT
Thus the python program was initiated and executed successfully.
