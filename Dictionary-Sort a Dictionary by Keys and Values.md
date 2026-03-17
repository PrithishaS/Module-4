# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
# Reg.No: 212222210020
# Name: Prithisha S

d = {'b': 2, 'a': 1, 'c': 3}

print("Sorted by keys:", dict(sorted(d.items())))
print("Sorted by values:", dict(sorted(d.items(), key=lambda item: item[1])))

## Sample Output
Sorted by keys: {'a': 1, 'b': 2, 'c': 3}
Sorted by values: {'a': 1, 'b': 2, 'c': 3}

## Result
The programs were implemented successfully and the outputs were verified.
