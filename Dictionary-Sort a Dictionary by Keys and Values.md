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
dict={'ravi':'10','rajnish':'9','sanjeev':'15','yash':'2','suraj':'32'}

a=sorted(dict.items(),key=lambda item:item[0])

print(f"OrderedDict({a})")

## Sample Output
<img width="1043" height="126" alt="image" src="https://github.com/user-attachments/assets/62592bec-6187-4d72-aafb-2ffacae7f469" />

## Result
Thus, the program has been executed successfully.
