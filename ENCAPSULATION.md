# Ex.No:6D
## Encapsulation
# AIM
To write a Python program to create a class Student with the private members name and age, and add getter and setter methods to initialize and modify the age variable.

# ALGORITHM
1.Start the Program.
2.Define the Student class.
3.Inside the Student class, define the __init__ method to initialize name and the private member __age.
4.Define a getter method get_age to return the value of the private member __age.
5.Define a setter method set_age to set a new value to the private member __age.
6.Create an object stud of the Student class with the name 'Jessa' and age 14.
7.Print the name and the age of stud using the getter method.
8.Use the setter method set_age to change the age of stud to 16.
9.Print the name and the updated age of stud using the getter method.
10.End the program.

# PROGRAM
```
Reg.No: 212222060089
Name:Jayashree B

class Student:
    def __init__(self, name, age):
        self.name = name
        self.__age = age
    def get_age(self):
        return self.__age
    def set_age(self, age):
        self.__age=age
    def get_name(self):
        return self.__name


stud = Student('Jessa', 14)

print('Name:', stud.name, stud.get_age())
stud.set_age(16)
print('Name:', stud.name, stud.get_age())
```

# OUTPUT
<img width="487" height="179" alt="image" src="https://github.com/user-attachments/assets/d4cfe9c0-aa4e-4800-892f-f71f687ce879" />


# RESULT
Thus the python program to create a class Student with the private members name and age, and add getter and setter methods has been executed.
