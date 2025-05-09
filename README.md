
# Multifactor Authenticator (TOTP-Based)

This project is a basic implementation of a time-based one-time password (TOTP) authenticator using Python. Created by *DolapotheEthicalHacker*, it simulates a secure login system using QR codes and OTPs generated via authenticator apps like Google Authenticator or Authy.

## 🔐 Features

- Time-based One-Time Password (TOTP) generation
-  OTP verification using pyotp
- QR code creation for easy setup with mobile authenticator apps
- Simple and clear user flow

## 📁 File

- file1.py: The main Python script containing the TOTP logic and QR code generation.

## 🛠 Requirements

Ensure you have Python 3 installed. You also need the following Python libraries:

- pyotp
- qrcode
- pillow (required for qrcode to display the image)

To install all requirements, run:

```bash
pip install pyotp qrcode pillow

Getting Started

git clone https://github.com/DolapotheEthicalHacker/Multifactor-Authenticator.git

cd Multifactor-Authenticator

Run the Script

python3 file1.py

Made with 💻 by DolapotheEthicalHacker

