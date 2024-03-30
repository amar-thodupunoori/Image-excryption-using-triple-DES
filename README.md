**Triple DES File Encryption and Decryption Tool**

This Python notebook contains functions for encrypting and decrypting files using the Triple DES (Data Encryption Standard) algorithm with CBC (Cipher Block Chaining) mode. It provides a simple yet secure way to protect your sensitive data.

*Features*

Encryption: Encrypt any type of file using a password of your choice.
Decryption: Decrypt files that have been encrypted using this tool, provided you have the correct password.
Password Security: The tool prompts the user to input a password twice to ensure accuracy and security. It enforces a minimum password length of 8 characters.
Data Integrity: The tool appends the hash of the original file to the encrypted data and verifies it during decryption to ensure data integrity.
User-Friendly Interface: The notebook provides clear instructions and prompts to guide the user through the encryption and decryption process.
Usage

Clone the Repository: Clone this repository to your local machine.

git clone https://github.com/your-username/triple-des-encryption.git

Install Dependencies: Ensure you have Python installed on your machine. Install the required dependencies using pip.

pip install pycryptodome

*Requirements*

Python 3.x
pycryptodome library
