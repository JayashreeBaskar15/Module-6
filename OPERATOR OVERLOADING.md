# Exp.No:27  
## Operator Overloading

---
# Ex.No:6B
## Operator Overloading
# AIM
To write a Python program to overload the division operator (/) in a user-defined complex class to perform division between two complex number objects and display the result.

# ALGORITHM
1.Start the program.
2.Define a class complex to represent complex numbers.
3.Create a constructor __init__() to initialize the real part a and imaginary part b.
4.Overload the division operator __truediv__() to divide the corresponding real and imaginary parts of two complex numbers. 
5.Overload the __str__() method to return the complex number in a readable format.
6.Create two objects Ob1 and Ob2 of the complex class with initial values.
7.Divide Ob1 by Ob2 using the overloaded division operator and store the result in Ob3.
8.Print the result Ob3.
9.End the program.
# PROGRAM
```
Reg.No: 212222060089
Name: Jayashree B

class complex:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def __truediv__(self, other):
        real=self.a/other.a
        imag=self.b/other.b
        return complex(real, imag)
    def __str__(self):
        return f"({self.a}, {self.b})"
Ob1 = complex(10, 21)
Ob2 = complex(2, 3)
Ob3 = Ob1 / Ob2
print(Ob3)
```

# OUTPUT
<img width="487" height="155" alt="image" src="https://github.com/user-attachments/assets/3245a6e6-241f-42a7-91e9-f0b75b0cf412" />


# RESULT
Thus, the program to overload the division operator for complex numbers was executed successfully and the output was verified.
### AIM  
To write a Python program to perform division of two complex numbers using the binary '/' operator overloading. Class name: `Complex`, where the objects `Ob1 = Complex(10, 21)` and `Ob2 = Complex(2, 3)` represent complex numbers.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the Complex class**:
   - Define the constructor `__init__()` to accept two parameters: `real` and `imag` (representing the real and imaginary parts of the complex number).
   - Assign these values to `self.real` and `self.imag` respectively.
3. **Define the `__truediv__()` method** to perform the division of two complex numbers:
   - Calculate the real part of the result as the division of `self.real` by `other.real`.
   - Calculate the imaginary part of the result as the division of `self.imag` by `other.imag`.
   - Return a new Complex object with the calculated real and imaginary parts.
4. **Define the `__repr__()` method** to represent the complex number as a string.
   - Return a string formatted to display the real and imaginary parts with one decimal place using `f"{self.real:.1f}, {self.imag:.1f}"`.
5. **Create two objects of the Complex class**:
   - `Ob1 = Complex(10, 21)` represents the complex number `10 + 21i`.
   - `Ob2 = Complex(2, 3)` represents the complex number `2 + 3i`.
6. **Perform the division operation**: Use the `/` operator to divide `Ob1` by `Ob2`. This will call the `__truediv__()` method.
7. **Print the result**: Print the result of the division, which will be formatted by the `__repr__()` method.
8. **End the Program.**

---

### PROGRAM

```

```

### OUTPUT


### RESULT

