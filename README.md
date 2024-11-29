
# AES Ransomware Script

## Overview

This script demonstrates the core mechanism of a basic ransomware attack using AES (Advanced Encryption Standard). AES is a symmetric encryption algorithm, meaning the same key is used for both encrypting and decrypting files. This type of ransomware encrypts a victim's files, making them inaccessible until they are decrypted with the correct key.

### How It Works

1. Encryption: 
   - The script scans the target directory for specific file types.
   - Using AES, it encrypts each file with a single symmetric key.
   - The encrypted files are saved with altered extensions, indicating they have been locked.

2. Decryption:
   - To decrypt the files, the same symmetric key is required along with a passphrase.
   - The passphrase acts as an additional layer of protection, ensuring that only authorized users with both the key and passphrase can recover the files.
   - Without the correct passphrase and key, recovering the files is nearly impossible due to the robustness of AES encryption.


### Purpose

This project is for **educational purposes only** to understand how ransomware operates. It emphasizes the importance of strong security measures, such as frequent backups and proper encryption management, to protect sensitive data.

### Legal Disclaimer

This code is strictly for learning and security research. Misusing it for malicious purposes is illegal and unethical. The author is not responsible for any misuse of this script.

--- 

Would you like to include a basic example or usage instructions as well?
