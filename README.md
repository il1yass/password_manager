# password_manager

This Python-based password manager offers a secure and convenient solution for storing and managing passwords. Here's a brief overview:

**Features:**
1. **User Registration:** Users can register by creating a master username and password.
2. **Login:** Registered users can securely log in using their master credentials.
3. **Password Storage:** The manager allows users to add passwords for various websites and securely store them.
4. **Password Retrieval:** Users can retrieve their stored passwords as needed.
5. **Encryption:** All passwords are encrypted using the Fernet symmetric encryption algorithm for enhanced security.
6. **Clipboard Support:** The manager supports copying passwords to the clipboard for easy pasting into login forms.

**How to Use:**
1. Run the Python script.
2. Choose between registration, login, or quitting the program.
3. After login, users can add passwords, retrieve passwords, view saved websites, or quit the program.

**Dependencies:**
- Python 3.x
- `hashlib`
- `getpass`
- `os`
- `pyperclip`
- `sys`
- `cryptography`

**Installation:**
1. Clone the repository.
2. Ensure Python and the required dependencies are installed.
3. Run the script using `python password_manager.py`.

**Security Note:**
- It's recommended to keep the encryption key (`encryption_key.key`) secure and backed up, as it's used to encrypt and decrypt passwords.

**Disclaimer:**
- This password manager is intended for personal use and should not be used for managing sensitive or critical passwords without proper evaluation of its security measures.
