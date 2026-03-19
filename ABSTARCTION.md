# Ex.No:6C
## Abstraction
# AIM
To write a Python program to define the abstract base class named Polygon and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the sides() method.
 
# ALGORITHM
1.Start the Program.

2.Import the ABC class from the abc module to implement abstraction.


3.Define the abstract base class Polygon

4.Inherit from ABC (Abstract Base Class).

5.Define an abstract method sides() with no implementation.

6.Define the Triangle class that inherits from Polygon

7.Implement the sides() method to print "Triangle has 3 sides".

8.Define the Pentagon class that inherits from Polygon

9.Implement the sides() method to print "Pentagon has 5 sides".

10.Define the Hexagon class that inherits from Polygon

11.Implement the sides() method to print "Hexagon has 6 sides".

12.Define the Square class that inherits from Polygon

13.Implement the sides() method to print "I have 4 sides".

14.Create an object t of the Triangle class and call the sides() method to print the number of sides.

15.Create an object s of the Square class and call the sides() method to print the number of sides.

16.Create an object p of the Pentagon class and call the sides() method to print the number of sides.

17.Create an object k of the Hexagon class and call the sides() method to print the number of sides.

18.End the Program.
# PROGRAM
```
from abc import ABC
class Polygon(ABC):   
  
   # abstract me  
   def sides(self):   
      pass  
  
class Triangle(Polygon):   
  
     
   def sides(self):   
      print("Triangle has 3 sides")   
  
class Pentagon(Polygon):   
    def sides(self):
        print("Pentagon has 5 sides")
class Hexagon(Polygon):   
    def sides(self):
        print("Hexagon has 6 sides")
class square(Polygon):   
  
   def sides(self):   
      print("I have 4 sides")   
  
# Driver code   
t = Triangle()   
t.sides() 
  
s = square()   
s.sides()  
  
p = Pentagon()   
p.sides() 
  
k = Hexagon()
k.sides()
```
# OUTPUT
<img width="884" height="242" alt="image" src="https://github.com/user-attachments/assets/7b29aef2-84cf-4a34-a2c7-862577c995b9" />


# RESULT
Thus,a Python program to define the abstract base class named Polygon and also define the abstract method are verified.
