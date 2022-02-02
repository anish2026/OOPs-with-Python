### OOP Exercise 4: Class Inheritance
Create a Bus class that inherits from the Vehicle class. Give the capacity argument of Bus.seating_capacity() a default value of 50.

```python 
class vehicle:
    def __init__(self,name,max_speed,mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage
        
    def seating_capacity(self,n):
        return n

        
class Bus(vehicle):
    def seating_capacity(self,n=50):
        return super().seating_capacity(n=50)
          
obj= Bus("Tata",120,35)
obj.__dict__
obj.seating_capacity()
```
output
```
50
```
