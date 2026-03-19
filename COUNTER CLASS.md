# Ex.No:6E
## COUNTER CLASS
# AIM
To write a Python program to create a Counter class that can increment the value of a counter.

# ALGORITHM
Start the Program.
1.Define the Counter class.

2.Initialize the current variable with 0.

3.Define the increment() method to increment the value of current by 1.

4.Define the value() method to return the current value of current.

5.Define the reset() method to reset the current value back to 0.

6.Create a counter object of the Counter class.

7.Call the increment() method three times to increment the counter.

8.Call the value() method and print the result to show the current counter value.

9.End the program.

# PROGRAM
```
# REGNO:212222060089
# Name:-Jayashree B
class Counter:
    def __init__(self):
        self.current = 0

    def increment(self):
        self.current += 1

    def value(self):
        return self.current

    def reset(self):
        self.current = 0

counter = Counter()
counter.increment()
counter.increment()
counter.increment()

print(counter.value())
```

# OUTPUT
<img width="741" height="164" alt="image" src="https://github.com/user-attachments/assets/64619c6a-c017-412b-a7d5-572c61049f38" />


# RESULT
Thus,a Python program to create a Counter class that can increment the value of a counter are verified.
