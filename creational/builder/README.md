# Builder Coding Exercise
You are asked to implement the Builder design pattern for rendering simple chunks of code.

Sample use of the builder you are asked to create:
```
cb = CodeBuilder('Person').add_field('name', '""')
                          .add_field('age', '0')
```

The expected output of the above code is:
```
class Person:
  def __init__(self):
    self.name = ""
    self.age = 0
```
