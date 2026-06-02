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
```
d={'c':'cat','a':'apple','b':'ball'}
print(dict(sorted(d.items())))
print(dict(sorted(d.items(),key=lambda item:item[1])))
```

## Sample Output
<img width="2096" height="393" alt="image" src="https://github.com/user-attachments/assets/acd186ed-d9c6-49a7-a830-84753393bec0" />

## Result
Thus the program has been successfully executed
