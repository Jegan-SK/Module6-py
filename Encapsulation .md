# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program

    class Rectangle:
    def __init__(self,length,breadth):
        self.__length=length
        self.__breadth=breadth
    def show(self):
        print(self.__length,self.__breadth)
    ob=Rectangle(3,4)
    ob.show()
## Output

<img width="1267" height="37" alt="image" src="https://github.com/user-attachments/assets/82ce6ee4-dc11-4984-b82d-18158d2ec84f" />

## Result
Thus the python program to implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`, is written and executed successfully.
