# OTP-Validation-Console-Based-project

## Overview
This Python script implements a simple **OTP (One-Time Password) verification system** using **SMTP (Simple Mail Transfer Protocol)**. It generates a **random OTP**, sends it via email, and verifies the user input to authenticate the OTP.

## Features
- ✅ **Generates a 4-digit random OTP**
- ✅ **Sends OTP via email** using Gmail SMTP
- ✅ **Ensures secure verification** with OTP matching
- ✅ **User-friendly and lightweight**

## Requirements
To run this script, you need:
- Python 3.x
- A Gmail account with **App Password enabled**
- The following Python libraries:
  ```sh
  pip install smtplib email.mime
  ```

## How to Run
1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   ```
2. **Navigate to the project folder**:
   ```sh
   cd OTP-Verification-System
   ```
3. **Modify the script**:
   - Replace `your_email@gmail.com` with your **Gmail ID**
   - Replace `your_app_password` with your **Gmail App Password**

4. **Run the script**:
   ```sh
   python otp_verification.py
   ```
5. **Enter recipient email** when prompted.
6. **Check your email for the OTP** and enter it in the script.
7. **If OTP matches, authentication is successful!** 🎉

## Configuration
### 🔐 Setting Up Gmail SMTP
Since Gmail no longer allows direct password authentication, you need to enable **2-Step Verification** and generate an **App Password**:
1. Go to **Google Account Security** settings.
2. Enable **2-Step Verification**.
3. Generate an **App Password** for "Mail".
4. Use this password in the script instead of your actual password.

## Disclaimer
🚨 **Security Warning:** Do **NOT** share or expose your email credentials in public repositories. Always use **environment variables** or **configuration files** to keep credentials secure.

## License
This project is licensed under the MIT License.

---

📧 **Need Help?** Feel free to raise an issue or contribute to improvements!

