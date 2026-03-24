## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = eval(input())
dict2 = eval(input())
def merge(d1, d2):
    merged_dict = {**d1, **d2}
    return merged_dict
result = merge(dict1, dict2)
print(result)
```

## Output
<img width="852" height="249" alt="image" src="https://github.com/user-attachments/assets/db9d3940-34aa-4313-94d5-8c18e51495fb" />

## Result
Thus the program executed successfully.
