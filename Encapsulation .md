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

```python
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth
        self.__display()

    def __display(self):
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")

rect = Rectangle(10, 5)

```

## Output

![image](https://github.com/user-attachments/assets/b3b151b3-2b09-4959-a4bc-88bd74641589)

## Result
Hence the program is executed successfully.
