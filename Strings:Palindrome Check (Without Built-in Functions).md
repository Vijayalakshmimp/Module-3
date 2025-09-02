# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"malayalam"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

def palindrome(a):

    flag=0

    for i in range(len(a)):
    
        if a[i]!=a[len(a)-i-1]:
        
            flag=1
    if not flag:
    
    
        print("The entered string is palindrome")
    
    else:
    
        print("The entered string is not palindrome")

string=input()

palindrome(string)

## Output
<img width="1168" height="285" alt="image" src="https://github.com/user-attachments/assets/fbe0997d-0c34-4f2b-a09e-58aa9a9a0748" />


## Result
Thus the Python program to check whether the string `"malayalam"` is a **palindrome** or not, without using built-in palindrome checking functions is executed and verified successfully.
