## Coding Examples

--- 
#### You can also run code and see output yourself!!!   
#### Click on 'Code' button on every example to run the code in online compiler

##### Python Class [Code](https://onecompiler.com/python/3y7h2hufs)  
```python
class Painter:
  def __init__(self, name, experience, place):
    self.name = name
    self.experience = experience
    self.place = place
    
  def info(self):
    print(self.name + " has " + self.experience + " years of experience and lives in " + self.place)
    
muneer = Painter("Muneer", "10", "Bettiah")
sanjeev = Painter("Sanjeev", "7", "Bettiah")

muneer.info();
sanjeev.info();
```

##### Python String Basics [Code](https://onecompiler.com/python/3y7c5jc9q)
```python
fruit = "banana"

# Length of string
print("Length of string :", len(fruit))

# While loop
index = 0
while index < len(fruit):
  letter = fruit[index]
  print(letter)
  index = index + 1

```