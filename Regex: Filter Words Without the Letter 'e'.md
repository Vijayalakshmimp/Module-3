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
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

lst=[]

for i in range(len(items)):

    res=re.match('.e.',items[i])
    
    if res:
    
        pass
    
    else:
    
        lst.append(items[i])

print(lst)
## Output
<img width="531" height="177" alt="image" src="https://github.com/user-attachments/assets/9d30c174-c165-4d91-8688-fba630f22a59" />

## Result
Thus the Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is executed and verified successfully.
