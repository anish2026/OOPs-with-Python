### OOP Exercise 5: Define a property that must have the same value for every class instance (object)
Define a class attribute”color” with a default value white. I.e., Every Vehicle should be white.

```python 
class Vehicle:
    color = "White"
    def __init__(self,name,max_speed,mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage
class Bus(Vehicle):
    pass
class Car(Vehicle):
    pass
obj1=Bus("Tata",120,35)

obj2=Car("Audi",180,15)

print(obj1.color)
print(obj2.color)
```
output
```
White
White
```
