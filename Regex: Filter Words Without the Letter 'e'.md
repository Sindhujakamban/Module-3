# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```

## Output
<img width="527" height="178" alt="544809644-a0436fef-1ff5-47d2-b326-83a52f1be69f" src="https://github.com/user-attachments/assets/e4533642-c952-4f11-86f6-bc4de563e454" />


## Result
Thus the program executed successfully.
