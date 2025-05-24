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
~~~

def remove(input_string, n):
    a = ""  
    for i in range(len(input_string)):
        if i != n:
            a += input_string[i]
    return a

user_string = input()

index = int(input())
result = remove(user_string, index)
print("String after removal:", result)

~~~

## Output
![image](https://github.com/user-attachments/assets/a329d75d-225b-4ccc-8d61-9978972b5a3a)

## Result
The python program is created and executed successfully.
