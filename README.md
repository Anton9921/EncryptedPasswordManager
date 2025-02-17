# EncryptedPasswordManager

Description:

This is a simple yet secure password manager built using Python and the cryptography library. It allows users to store, view, and delete credentials in an encrypted format, ensuring password security. The encryption key is stored separately from the credentials file to maintain confidentiality. The program provides an interactive command-line interface for managing passwords efficiently.

Features:

Encryption: Uses the Fernet encryption algorithm to secure stored credentials.
Secure Key Management: Generates and stores an encryption key separately.
Add Credentials: Users can store multiple credentials securely.
View Credentials: Displays stored credentials in decrypted form.
Delete Credentials: Allows removal of specific credentials.
Error Handling: Provides warnings for invalid inputs and corrupted data.

Installation:

Clone the repository:
git clone https://github.com/Anton9921/encrypted-password-manager.git

Navigate to the project directory:
cd encrypted-password-manager

Install required dependencies:
pip install cryptography

Usage:

Run the program using:
python password_manager.py

Follow the on-screen prompts to add, view, or delete credentials.

Security Notes:

Keep the key.key file secure; losing it will prevent access to stored passwords.
Do not share the credentials file without encrypting it separately.

License:

This project is open-source and available under the MIT License.

Contributing:

Pull requests and feature suggestions are welcome. Feel free to fork the repository and submit a PR!

Author

 Anton Pervukhin - Pervukhin333@gmail.com

