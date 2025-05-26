# Exp.No:22  
## DESTRUCTOR

---

### AIM  
To write a Python program that demonstrates the use of a destructor method __del__() to delete an instance of a class and perform a cleanup operation.

---

### ALGORITHM

Start the program.

Define a class named Awesome.

Inside the class:

Define a method greetings() to print a message with name and age.

Define the destructor method __del__() that prints a message when the object is deleted.

Create an object obj of the class Awesome.

Call the greetings() method using the object.

Allow the program to finish, triggering the destructor automatically.

End the program.

---

### PROGRAM

```
class Awesome:

    # some method
    def greetings(self):
        print("My name is Vishvajit Rao and I am 22 years old.")

    # the destructor method
    def __del__(self):
        print("Vishvajit Rao student is deleted.")

# object of the class
obj = Awesome()
obj.greetings()

```

### OUTPUT
![Screenshot (244)](https://github.com/user-attachments/assets/163bd4e0-84e4-488e-b968-e7ac77ba2a66)


### RESULT
Thus the python program was initialised and executed successfully.
