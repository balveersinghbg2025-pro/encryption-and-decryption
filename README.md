# 🔐 XOR Text & File Encryption using NumPy

A simple yet effective implementation of XOR-based encryption and decryption for text and files using NumPy arrays.

This project demonstrates how to:
- Encrypt plain text into numerical arrays
- Store encrypted data in `.txt` files
- Decrypt encrypted arrays back to original text

---

## 📌 Features

✔️ Encrypt any string using XOR  
✔️ Encrypt entire text files line-by-line  
✔️ Store encrypted output as comma-separated values  
✔️ Decrypt back to original readable text  
✔️ Uses efficient NumPy vectorized operations  

---

## 🛠️ Technologies Used

- Python 🐍  
- NumPy 📊  

---

## 📂 Project Structure
├── encryption.py
├── message.txt
└── README.md

---

## ⚙️ How It Works

### 🔑 XOR Encryption Logic

Each character is converted into its ASCII value and then XORed with a key:
Encrypted = ASCII_Value ⊕ Key
Decrypted = Encrypted ⊕ Key
