# Exp.No:26  
## Method Overriding

---

### AIM  
To write a Python program to create a Parent class `Bird` and inherit two child classes `Sparrow` and `Ostrich` from the `Bird` class with the same method `flight()`. Create an object for each class and call the methods of the class which will print the name of the bird that is flying.

---

### ALGORITHM

1. **Begin the program.**
2. **Define the Bird class**:
   - Create a method `intro()` to print "There are many types of birds."
   - Create a method `flight()` to print "Most of the birds can fly but some cannot."
3. **Define the Sparrow class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Sparrows can fly."
4. **Define the Ostrich class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Ostriches cannot fly."
5. **Create an object `obj_bird`** of the `Bird` class.
6. **Create an object `obj_spr`** of the `Sparrow` class.
7. **Create an object `obj_ost`** of the `Ostrich` class.
8. **Print the general message** "There are many types of birds."
9. **Call the `flight()` method** on each object (`obj_bird`, `obj_spr`, `obj_ost`) to display the respective messages.
10. **Terminate the program.**

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
class A:
    def __init__(self, val):
        self.val = val

    def __add__(self, other):
        return A(self.val + other.val)

    def __str__(self):
        return str(self.val)

a = int(input())
b = int(input())
c = input()
d = input()

obj1 = A(a)
obj2 = A(b)
obj3 = A(c)
obj4 = A(d)

print(": ", obj1 + obj2)
print(": ", obj3 + obj4)
```

### OUTPUT
<img width="430" height="225" alt="image" src="https://github.com/user-attachments/assets/95ff4c17-ad7c-425e-a43f-5e87ee4f075b" />


### RESULT
Thus, the Python program to overload the + operator for adding two objects has been successfully executed and the output is verified.
