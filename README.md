# Task2-Palindrome_Checker
Description: Implement a program that checks whether a given word or phrase is a palindrome. A palindrome is a word or phrase that reads the same forwards and backward, ignoring spaces and punctuation. Skills: String manipulation, loops, conditional statements.
# Palindrome Checker

A Java console program that checks whether a word or phrase reads the same forward and backward.

## Requirements covered

- Accepts a word or full phrase as input.
- Ignores uppercase/lowercase differences.
- Ignores spaces and punctuation.
- Uses string manipulation, a loop, and conditional statements.

## How to run

Open a terminal in this folder and run:

```powershell
javac PalindromeChecker.java
java PalindromeChecker
```

## Example inputs

| Input | Expected result |
| --- | --- |
| `madam` | Palindrome |
| `Race car` | Palindrome |
| `A man, a plan, a canal: Panama!` | Palindrome |
| `Java` | Not a palindrome |

## How it works

The program removes every character except letters and numbers, converts the remaining text to lowercase, and then compares the first and last characters. It moves inward one character at a time. If any pair differs, the text is not a palindrome.
