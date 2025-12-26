# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

```class student():
    def __init__(self, name):
        self.name=name
        print("This is non parametrized constructor")
    def display(self):
        greetings = "Hello"
        print(greetings, self.name)

name=input()
c=student(name)
c.display()
```




## Output
<img width="1116" height="240" alt="image" src="https://github.com/user-attachments/assets/8dd4fe25-f376-4d8e-b3c4-cdfd913a4028" />


## Result
Thus the programme executed successfully
