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
```python
text = "google"
rev_text = text[::-1]

if text == rev_text:
    print(text, "is a Palindrome")
else:
    print(text, "is Not a Palindrome")

## Output
google is Not a Palindrome

## Result
The program successfully checks whether the string "google" is a palindrome or not (without using built-in functions).
