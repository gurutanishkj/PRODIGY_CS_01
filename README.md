# PRODIGY_CS_01
Caesar Cipher encryption and decryption implementation in Python - Prodigy InfoTech Cyber Security Internship Task 01


Description

A Python program that encrypts and decrypts text using the Caesar Cipher algorithm.

Features

- Encrypts plaintext using a shift value.
- Decrypts ciphertext back to the original message.
- Supports both uppercase and lowercase letters.
- Preserves spaces, numbers, and special characters.

How It Works

- "ce()" function shifts each alphabet character forward by the given shift value.
- "cd()" function shifts the characters backward to retrieve the original message.
- Uppercase and lowercase letters are handled separately.
- Non-alphabetic characters remain unchanged.

Code Explanation

- "ord(char)" converts a character into its ASCII value.
- "% 26" ensures circular shifting (after Z comes A).
- "chr()" converts the ASCII value back into a character.

Technologies Used

- Python 3

How to Run

python caesar program.py

Example

Input

Enter message: Gurutanish

Enter shift value: 6

Output

Encrypted text: Maxazgtoyn

Decrypted text: Gurutanish
