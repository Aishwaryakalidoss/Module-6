# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
from abc import ABC, abstractmethod

class Payment(ABC):
    @abstractmethod
    def payment(self, amount):
        pass

class CreditCardPayment(Payment):
    def payment(self, amount):
        print("Credit card payment of- ", amount)
        print("Purchase of amount- ", amount)
        return True

class MobileWalletPayment(Payment):
    def payment(self, amount):
        print("Mobile wallet payment of- ", amount)
        print("Purchase of amount- ", amount)
        return True

obj1 = CreditCardPayment()
print(obj1.payment(100))

obj2 = MobileWalletPayment()
print(obj2.payment(200))
```

### OUTPUT
<img width="664" height="209" alt="image" src="https://github.com/user-attachments/assets/c4b7d300-b4e9-4d1c-a0ec-a65f6955fd0b" />


### RESULT
Thus, the Python program to create an abstract class Payment with subclasses CreditCardPayment and MobileWalletPayment has been successfully executed and the output is verified.
