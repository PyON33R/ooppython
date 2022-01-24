# ooppython.github.io

## OOP

I will not go over all of the theoretical principles in detail.
OOP stands for object-oriented programming, and that's all you need to know about it now.

Take a look at the following code:

```
class Person:
    def __init__(self, name:str, age:int, country:str):
        self.name = name
        self.age = age
        self.country = country
```

In python we can define a Blueprint with class keyword. Yes, above code is a blueprint of a concept (Person). 
Using the blueprint, you may create a Person with attributes such as name, age, and nationality. 

Here, I make two: 

```
p1 = Person('abir sarkar', 29, 'India') # self in the class definition will automatically get replaced by p1 here
p2 = Person('muhmmad bhattacharya', 35, 'Pakistan') # p2 will take over ^
print(p1.name) # this will print the value of the name attribute
```
You may call ```__init__``` the constructor. It makes no difference what you call it. What it accomplishes is critical.
It is a specific method that is called automatically whenever a new object (such as p1/p2) is created from blueprint.

```Person('abir sarkar', 29, 'India')``` -> arguments passed here, go straight to the ```__init__``` method. 
