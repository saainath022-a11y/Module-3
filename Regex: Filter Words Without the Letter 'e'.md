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
Add code here
import re
l=[]
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r'e',i):
        l.append(i)
print(l)
## Output
<img width="513" height="202" alt="mod 3 2" src="https://github.com/user-attachments/assets/6291de28-c92d-4e74-a747-bb386b4215bf" />

## Result
Successfully wrote a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

