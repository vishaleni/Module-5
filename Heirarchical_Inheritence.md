# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program

```class Details:
    def __init__(self, id, name, gender, hospital, department):
        self.id = id
        self.name = name
        self.gender = gender
        self.hospital = hospital
        self.department = department

    def display(self):
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)
        print("Hospital: ", self.hospital)
        print("Department: ", self.department)
        print()


class Doctor(Details):
    pass


class Patient(Details):
    pass


# Taking Doctor details
id1 = int(input())
name1 = input()
gender1 = input()
hospital1 = input()
department1 = input()

doctor = Doctor(id1, name1, gender1, hospital1, department1)

# Taking Patient details
id2 = int(input())
name2 = input()
gender2 = input()
hospital2 = input()
department2 = input()

patient = Patient(id2, name2, gender2, hospital2, department2)

# Display output
print("Doctor Object")
doctor.display()

print("Patient Object")
patient.display()
```
## Sample Output
<img width="1129" height="459" alt="image" src="https://github.com/user-attachments/assets/55eeab09-c768-4ef8-b334-666a880e3732" />
Result:
Thus, the programme was executed successfully


