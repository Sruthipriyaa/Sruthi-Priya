# overview

This project is a keylogger that captures keystrokes, checks for forbidden keywords, encrypts sensitive data, and sends alerts via email. It is intended for educational purposes and should be used responsibly.

# snapshots

![output](https://github.com/user-attachments/assets/ba290d46-d2b5-4d33-afb5-271272750d32)
![scrnshot capture](https://github.com/user-attachments/assets/3ecfd5e6-e3d5-4ef3-87d3-dc103dff22e7)
![EMAIL](https://github.com/user-attachments/assets/b9d2301a-bdad-427a-9d79-c35e27ce6231)
![generate key output](https://github.com/user-attachments/assets/5b21e07d-e36e-48e4-8488-c545ee7da76f)
![decryption  pic](https://github.com/user-attachments/assets/e6dc4b4c-b656-4f06-a2a3-8774df5e3722)

# Inputs To Mail

Get Keyboard,ScreenShot,Microphone Inputs and Send to your Mail. 


# Features

1.Keystroke Logging: Captures all keystrokes typed by the user.

2.Forbidden Keyword Detection: Checks for a list of predefined forbidden keywords.

3.Data Encryption: Encrypts captured data, including keystrokes, system info, clipboard content, and screenshots.

4.Alarm Triggering: Triggers an alarm sound when forbidden keywords are detected.

5.Microphone Recording: Records audio when forbidden keywords are detected.

6.Email Notifications: Sends email notifications with encrypted attachments when forbidden keywords are detected.

7.System Information Collection: Captures and encrypts system information.

8.Clipboard Monitoring: Captures and encrypts clipboard content.


9.Screenshot Capture: Takes screenshots and saves them without encryption.

# Installation

1.Install Required Packages:

   pip install -r requirements.txt

   Packages: time, winsound, smtplib, email, pyperclip, pyautogui, sounddevice, numpy, scipy, pynput, cryptography, platform, socket, requests, base64

2.Configure Email Settings:

 Update the sender_email, receiver_email, and email_password variables with your email credentials.













