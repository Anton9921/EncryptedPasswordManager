# 🔐 Encrypted Password Manager

## Overview
A secure and simple password manager built with Python using the `cryptography` library. It encrypts stored credentials, ensuring password safety with an easy-to-use command-line interface.

## Features
- 🔒 **Encryption:** Protects credentials using the Fernet encryption algorithm.
- 🔑 **Secure Key Management:** Generates and stores encryption keys separately.
- ➕ **Add Credentials:** Save multiple accounts securely.
- 👀 **View Credentials:** Decrypt and access stored passwords.
- ❌ **Delete Credentials:** Remove specific accounts.
- ⚠️ **Error Handling:** Warns against invalid inputs or corrupted data.

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/Anton9921/EncryptedPasswordManager.git

# Navigate to the project directory
cd EncryptedPasswordManager

# Install dependencies
pip install cryptography
```

## 🚀 Usage
```bash
python password_manager.py
```
Follow the on-screen prompts to manage passwords efficiently.

## 🔑 Security Notes
- Keep `key.key` safe—losing it means losing access to your passwords.
- Do not share the credentials file unless separately encrypted.

## 📜 License
MIT License

## 🤝 Contributing
Pull requests and suggestions are welcome!

## ✍️ Author
**Anton Pervukhin**  
📧 Pervukhin333@gmail.com



