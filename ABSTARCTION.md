# Exp.No:28  
## Abstraction

---

### AIM  
To write a Python program to define the abstract class Animal with an abstract method feed() which is implemented in the subclasses Lion,Panda,Snake ,invoke the method using the object of the classes.


### ALGORITHM



### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
from abc import ABC, abstractmethod
class Animal(ABC): # Inherit from ABC(Abstract base class)
   def feed(self):
       pass
class Lion(Animal):
   def feed(self):
       print("Feeding a lion with raw meat!")
class Panda(Animal): 
    def feed(self): 
        print("Feeding a panda with some tasty bamboo!") 

class Snake(Animal): 
    def feed(self): 
        print("Feeding a snake with mice!")
zoo = [Lion(), Panda(), Snake()]

for animal in zoo:
    animal.feed()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/564cc194-dce7-4a93-969a-b6e0810c4ef7)

### RESULT
Thus the Python program to define the abstract class Animal with an abstract method feed() which is implemented in the subclasses Lion,Panda,Snake ,invoke the method using the object of the classes is executed successfully.
