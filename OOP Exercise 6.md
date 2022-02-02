### OOP Exercise 6: Class Inheritance
Create a Bus child class that inherits from the Vehicle class. The default fare charge of any vehicle is seating capacity * 100. If Vehicle is Bus instance, we need to add an extra 10% on full fare as a maintenance charge. So total fare for bus instance will become the final amount = total fare + 10% of the total fare.

Note: The bus seating capacity is 50. so the final fare amount should be 5500. You need to override the `fare()` method of a Vehicle class in Bus class.

```python

class vehicle:
    
    def __init__(self,name,mileage,capacity):
        self.name = name
        self.mileage = mileage
        self.capacity = capacity
        
    def fare(self):
        return self.capacity*100

class bus(vehicle):
    def fare(self):
        total=super().fare()
        total = total + (10*total)/100
        return total 
obj=bus("Volvo",10,50)  
obj.fare() 
```
output
```
550.0
```
