### OOP Exercise 3: Create a child class Bus that will inherit all of the variables and methods of the Vehicle class

```python
class vehicle:
    def __init__(self,max_speed,mileage):
        self.max_speed = max_speed
        self.mileage = mileage
class Bus(vehicle):
    pass
  
        
obj=Bus(120,15)
print(obj.max_speed)
print(obj.mileage)
```
output
```
120
15
```
