## Exercise: Class and Objects

1. Create a sample class named Employee with two attributes id and name 

```
class Employee:
    def __init__(self, id, name):
        self.id = id
        self.name = name

E1 = Employee(9, "nam")
print(E1.id, E1.name)
del E1.id
del E1

```
object initializes id and name dynamically for every Employee object created.
 
```


```

2. Use del property to first delete id attribute and then the entire object
```
```

[Solution](https://github.com/codebasics/py/blob/master/Basics/Exercise/16_class_and_objects/16_class_and_objects.py)
