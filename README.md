# 🔐 Caesar Cipher — Python

A simple **interactive text encryption and decryption program built with Python**, based on the classic Caesar Cipher technique.

The program allows users to enter a message and shift value, then **encrypt or decrypt the message** by shifting alphabetic characters through the alphabet.

## ✨ Features

* 🔒 Encrypt messages using a custom shift
* 🔓 Decrypt encrypted messages
* 🔄 Supports multiple encryption/decryption operations
* 🔢 Allows the user to choose the shift amount
* 🔤 Preserves uppercase and lowercase letters
* ✏️ Keeps spaces and special characters unchanged
* ⚠️ Handles invalid user input
* 🖥️ Interactive command-line interface

## 🧠 How It Works

The Caesar Cipher is a substitution cipher that shifts each letter in a message by a fixed number of positions in the alphabet.

For example, with a shift of **3**:

```text
Original:  HELLO
Encrypted: KHOOR
```

Decrypting the encrypted message with the same shift returns the original text:

```text
Encrypted: KHOOR
Decrypted: HELLO
```

The program automatically wraps around the alphabet when necessary:

```text
Z + 3 → C
```

## 🔄 Program Flow

```text
Start
  ↓
Choose Encrypt / Decrypt
  ↓
Enter Message
  ↓
Enter Shift Amount
  ↓
Process Characters
  ↓
Display Result
  ↓
Continue or Exit
```

## 🛠️ Tech Stack

* **Python 3**
* Python Standard Library
* Command Line / Terminal

## 📚 Python Concepts Practiced

This project helped me practice:

* Functions
* Loops
* Conditional statements
* String manipulation
* Character encoding concepts
* User input
* Input validation
* Modular programming
* Lists and/or string operations
* Working with ASCII / character positions
* Problem-solving and program logic

## 💻 Example

```text
================================
        CAESAR CIPHER
================================

1. Encrypt
2. Decrypt
3. Exit

Choose an option: 1

Enter your message: Hello World
Enter shift amount: 3

Encrypted message: Khoor Zruog
```

## 🎯 Project Objective

The goal of this project was to understand the fundamentals of **encryption and text transformation** while strengthening my Python programming skills.

It demonstrates how a simple mathematical transformation can be applied to characters to create an encryption and decryption system.

## 🔮 Future Improvements

Possible improvements for future versions:

* 🧩 Add automatic brute-force decryption
* 🔑 Add stronger encryption algorithms
* 📄 Support text files
* 💾 Save encrypted messages
* 🎨 Create a graphical user interface
* 🔐 Add password-based encryption
* 📊 Add frequency-analysis tools

## 👩‍💻 Author

**Carla Rizk**

Computer Science Student | Technical Support Specialist | Aspiring Software Developer

---

⭐ **A Python project exploring the fundamentals of encryption, character manipulation, and algorithmic problem-solving.**

