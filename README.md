# SAAINATH.B

# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

Add code here
l=[1,2,3,4,5,6,7,8,9]
print(sum(l))

## Output
<img width="273" height="92" alt="mod 3 1" src="https://github.com/user-attachments/assets/50dab6c6-35f0-4cf4-9fcd-12d0a7add363" />

## Result
Successfully wrote a Python program that calculates the sum of all elements in a list.

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

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
Add Code Here
string=input()
n=int(input())
es=''
for i in range(len(string)):
    if i!=n:
        es+=string[i]
print(es)
## Output
<img width="311" height="238" alt="mod 3 3" src="https://github.com/user-attachments/assets/f4fdcc99-1ba6-4e58-a171-60d3fa2f5546" />

## Result
Successfully wrote a Python program that accepts a string and removes the character at a specified index.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

Add code here
string="google"
print("the string is a palindrome." if string==string[::-1] else " it is not a palindrome")

## Output
<img width="906" height="92" alt="mod 3 4" src="https://github.com/user-attachments/assets/6f5c5e03-78fd-40aa-b8ff-dc7a1e671a9a" />

## Result
Successfully wrote a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
Add code here
tuple_=eval(input())
print('n' in tuple_)
print('8' in tuple_)
## Output
<img width="393" height="122" alt="mod 3 5" src="https://github.com/user-attachments/assets/d9bf60f3-fca6-4452-a6d2-93d8c2e32ac4" />

## Result
Successfully wrote a Python program that checks if the element 'n' and the element 8 exist within a given tuple.


