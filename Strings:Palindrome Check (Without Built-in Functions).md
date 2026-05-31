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
```
string = "google"

rev = string[::-1]

if string == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```
## Output

<img width="236" height="50" alt="image" src="https://github.com/user-attachments/assets/e247c160-09b3-47b7-b7f6-1dd20f6f0fc0" />


## Result
Thus, the Python program to check whether the string "google" is a palindrome or not was executed successfully and the output was verified.
