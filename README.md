Vigenère Cipher - Python Implementation
This repository contains a Python implementation of the Vigenère Cipher, a classical encryption technique that encodes or decodes a message using a custom key.

Features
Encrypt Text: Encode a given message using the Vigenère cipher and a custom key.
Decrypt Text: Decode an encrypted message back to its original form using the same key.
User Input: Allows dynamic input for both the text to be processed and the custom key.
Code Overview
The implementation includes:

vigenere function: Core logic for the encryption and decryption process.
encrypt function: Simplifies encryption calls.
decrypt function: Simplifies decryption calls.
The script is interactive and requires user input for:

The text to encrypt or decrypt.
The custom key to be used for the cipher.
Example Use Case
Text Input: aospw'u zhmgivdt rmphhag? o jabt, g uoz, q tua cgjqjsg—artk htan!
Custom Key: happycoding
Decryption Output: "Today's LeetCode contest? I came, I saw, I got crushed—send help!"
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:
bash
Copy code
cd your-repo-name
Run the script:
bash
Copy code
python vigenere_cipher.py
Enter the text and custom key when prompted.
Testing the Script
Encrypt or decrypt messages by providing inputs interactively.
Modify the custom_key and text variables to test predefined cases.
Contributing
Contributions are welcome! If you'd like to improve the code or add features, feel free to submit a pull request.

License
This project is open-source and available under the MIT License.
