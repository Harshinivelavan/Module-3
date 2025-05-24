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
~~~

string = "google"


reversed_string = string[::-1]

if string == reversed_string:
    print(f'"{string}" is a palindrome.')
else:
    print(f'"{string}" is not a palindrome.')

~~~

## Output
![image](https://github.com/user-attachments/assets/1db3184f-e8fb-46cb-991f-949de0893286)

## Result
The python program is created and executed successfully.
