# -4-Secure-Data-Encryption-System
Secure Data Encryption System A Streamlit app that securely stores and retrieves data using unique passkeys. It encrypts data with AES and hashes passkeys with SHA-256, featuring authentication and reauthorization after failed attempts.

Secure Data Encryption System
Description
A Streamlit-based web application that securely stores and retrieves user data using unique passkeys. The system encrypts data with AES encryption, hashes passkeys with SHA-256, and provides a reauthorization mechanism after multiple failed decryption attempts. The application operates entirely in-memory and does not require an external database.

Features
Data Encryption: Encrypts user data using AES encryption.

Passkey Hashing: Passkeys are securely hashed using SHA-256.

Authentication: Provides authentication and reauthorization after failed attempts.

Store Data: Users can securely store data with a unique passkey.

Retrieve Data: Users can decrypt and retrieve stored data using the correct passkey.

Failed Attempts: After three failed attempts, users are forced to reauthenticate.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/secure-data-encryption-system.git
Navigate to the project directory:

bash
Copy
Edit
cd secure-data-encryption-system
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Usage
Store Data: Navigate to the "Store Data" page, enter data and a passkey, and store the data securely.

Retrieve Data: Navigate to the "Retrieve Data" page, enter the encrypted data and passkey, and decrypt it to view the stored information.

Reauthentication: If three failed decryption attempts are made, a reauthentication (login) is required before retrying.

License
This project is licensed under the MIT License - see the LICENSE file for details.
