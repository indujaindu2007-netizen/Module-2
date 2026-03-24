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

<img width="1016" height="353" alt="image" src="https://github.com/user-attachments/assets/2416a1b4-797f-4072-bf4e-2d29dd0bee5d" />

## Output
<img width="1270" height="303" alt="image" src="https://github.com/user-attachments/assets/015b57d7-16d4-4bbc-a287-a0e55e8fad6b" />

## Result
Thus, the Python program successfully checks whether the given number is a palindrome using loops and displays the correct re
