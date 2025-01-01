# Secret Communication using Cryptography and Steganography

## Overview
This project implements a secure communication system that combines **RSA encryption** and **LSB steganography** to provide a dual-layer approach for safeguarding messages. It encrypts sensitive messages and hides them within images, ensuring confidentiality and stealth in data transmission.

## Key Features
- **RSA Encryption**: Ensures data confidentiality through public and private key encryption.
- **LSB Steganography**: Embeds encrypted messages into images by modifying the least significant bits of pixel values.
- **Dual-Layer Security**: Combines encryption and steganography for enhanced protection against unauthorized access.
- **Python Implementation**: Simple and efficient design leveraging Python's cryptographic and image processing libraries.

## Technologies Used
- **Programming Language**: Python
- **Cryptography**: RSA encryption
- **Image Processing**: LSB steganography

## How It Works
1. **Message Encryption**:
   - The message is encrypted using the RSA algorithm, generating a secure ciphertext.

2. **Message Embedding**:
   - The encrypted message is hidden within an image file using the LSB (Least Significant Bit) steganography method.

3. **Message Extraction & Decryption**:
   - The hidden message is extracted from the image and decrypted using the private key to reveal the original message.
