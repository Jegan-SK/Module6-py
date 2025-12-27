# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program

    from abc import abstractmethod,ABC
    class shape:
        @abstractmethod
        def calculate_area(self):
        pass
    class Rectangle(shape):
        def __init__(self,l,b):
            self.l=l
            self.b=b
        def calculate_area(self):
            return self.l*self.b
    class Circle(shape):
        def __init__(self,r):
            self.r=r
        def calculate_area(self):
            return 3.1415*self.r**2
    ob1=Rectangle(2,5)
    ob2=Circle(4)
    for i in [ob1,ob2]:
        print(i.calculate_area())
        
## Output

<img width="1247" height="63" alt="image" src="https://github.com/user-attachments/assets/c1a4a257-cb0c-40c1-914e-ca588eb93a59" />


## Result

Thus the python program to create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle` , is written and executed succssfully.
