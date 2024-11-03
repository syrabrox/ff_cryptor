# FF-Cryptor

## Features
- **Secure Password Input**:
   - The program prompts the user for a master password while masking the input with asterisks for privacy.
   - Utilizes SHA-256 hashing to generate a secure key from the user-provided password.

- **Multiple Encryption Algorithms**:
  - Selects from various encryption algorithms based on the length of the password, adapting to different security needs:
    - ChaCha20 for short passwords.
    - AES-256 in ECB mode for medium passwords.
    - Triple DES (3DES) in CBC mode for longer passwords.

- **File and Folder Support**: 
  - Encrypts and decrypts individual files.
  - Recursively encrypts or decrypts all files within a specified folder.

- **Automatic File Renaming**: 
  - Encrypted files are renamed with a `.crypted` extension.
  - Decrypted files have the `.crypted` extension removed.

## License
This project is licensed under the MIT License.

## Author
Created by www.cr4ck.de team.
