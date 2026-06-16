Caesar Cipher Encryption and Decryption in Python
Prodigy InfoTech Cyber Security Internship – Task 01
Description

This project implements the Caesar Cipher algorithm using Python. The program encrypts a message by shifting each alphabetic character by a user-defined shift value and then decrypts it back to the original message.

Features
Encrypts text using a shift value.
Decrypts encrypted text back to the original message.
Supports both uppercase and lowercase letters.
Preserves spaces, numbers, and special characters.
Simple and easy-to-understand implementation.
How the Code Works
Encryption Function - ce(x, y)
x stores the input message.
y stores the shift value.
Each character in the message is checked.
If the character is a letter, it is shifted forward by the given value.
If the character is not a letter, it remains unchanged.
ASCII Conversion
ord() converts a character into its ASCII value.
chr() converts an ASCII value back into a character.
65 represents the ASCII value of uppercase 'A'.
97 represents the ASCII value of lowercase 'a'.
Modulo Operation
% 26 ensures that the alphabet wraps around correctly.
Example:
Z shifted by 1 becomes A.
z shifted by 1 becomes a.
Decryption Function - cd(x, y)
Uses the encryption function with a negative shift value.
Restores the encrypted text back to the original message.
Technologies Used
Python 3
How to Run
python caesar_cipher.py
Example
Input
Enter message: gurutanish
Enter shift value: 6
Output
Encrypted Text: maxazgtoyn
Decrypted Text: gurutanish
