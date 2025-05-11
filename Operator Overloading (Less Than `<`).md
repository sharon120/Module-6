# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program

```python
class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"

val1 = int(input("Enter value for ob1: "))
val2 = int(input("Enter value for ob2: "))

ob1 = A(val1)
ob2 = A(val2)

print(ob1 < ob2)

```

## Output

![image](https://github.com/user-attachments/assets/f2fd09b3-e62a-47f1-bc63-fa3b0cf2ed2a)

![image](https://github.com/user-attachments/assets/2a703d84-2cec-4345-9144-aead31b05b2d)

## Result
Hence the program is executed successfully.
