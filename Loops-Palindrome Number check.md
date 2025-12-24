## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="841" height="287" alt="image" src="https://github.com/user-attachments/assets/6d0af816-3b10-45a8-b625-bdb7f8ce7f9b" />

## Output
<img width="1092" height="261" alt="image" src="https://github.com/user-attachments/assets/21d75684-0d60-409b-b989-cdcaccc244d6" />


## Result
Thus, the Python program successfully checks whether the given number is a palindrome using loops and displays the correct result.
