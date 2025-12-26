# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program

```class Demo:
    def live(self):
        print("Alive")
    def __del__(self):
        print("The object no longer exists")
obj=Demo()
obj.live()
del obj
```
        


## 🧪 Output

<img width="613" height="114" alt="image" src="https://github.com/user-attachments/assets/f9247bff-6a5f-4f89-9089-4d1c8511cc54" />


## Result
Thus , the programme executed successfully

