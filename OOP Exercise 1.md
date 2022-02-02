### OOP Exercise 1: Create a Class with instance attributes

Write a Python program to create a Vehicle class with max_speed and mileage instance attributes.

```python
class Vehicle:
  def __init__(self,max_speed,mileage):
    self.max_speed = max_speed
    self.mileage = mileage
Alto=Vehicle(100,15)
print(Alto.max_speed)
print(Alto.mileage)
  ```
  
  Output:
  ```
  100
  15
  ```
