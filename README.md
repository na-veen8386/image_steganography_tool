# 🖼️ Image Steganography using Cipher Suite

This project demonstrates how to **securely hide and transmit encrypted messages within images** using steganography techniques and the **Fernet Cipher Suite**. Developed as part of a Cybersecurity Internship at **Supraja Technologies**, this application features GUI-based encryption, decryption, and email integration.


## 📌 Project Summary

- **Title**: Image Steganography using Cipher Suite
- **Description**: Encrypt a message and hide it in an image. Send it securely via email.
- **Technologies**: `Python`, `Tkinter`, `Fernet (Cryptography)`, `SMTP`, `PIL`
- **Intern**: Kalanjeri Naveen Prasad
- **Organization**: Supraja Technologies
- **Duration**: 26-May-2024 to 29-June-2024

---

## 📂 Features

✅ GUI with Tkinter  
✅ Image-based encryption & decryption using `Fernet`  
✅ Send encrypted image + message via Gmail SMTP  
✅ Secure decryption with key file validation  
✅ Project info shown in browser with dynamic HTML  

---

## 🧑‍💻 Developer Information

- **Name**: Kalanjeri Naveen Prasad
- **Intern ID**: ST#IS#6407
- **Email**: kalamjerinaveenprasad@gmail.com

---

## 🏢 Company Details

- **Organization**: Supraja Technologies
- **Email**: contact@suprajatechnologies.com

---

<div>
  <h2>📧 Gmail App Password Creation Process</h2>
  <p>To allow your Python application to send emails via Gmail, follow these steps to generate an App Password:</p>

  <ol>
    <li>
      <strong>Enable 2-Step Verification</strong>
      <ul>
        <li>Go to <a href="https://myaccount.google.com/security" target="_blank">Google Account Security</a>.</li>
        <li>Under "Signing in to Google", enable <strong>2-Step Verification</strong>.</li>
      </ul>
    </li>
  </ol>
    <li>
      <strong>Generate an App Password</strong>
      <ul>
        <li>After enabling 2-Step Verification, go to the <a href="https://myaccount.google.com/apppasswords" target="_blank">App Passwords</a> page.</li>
        <li>You might need to re-enter your Google password.</li>
        <li>In the "Select app" dropdown, choose <strong>Mail</strong>.</li>
        <li>In the "Select device" dropdown, choose <strong>Other</strong>, then enter a custom name (e.g., <em>Python App</em>).</li>
        <li>Click <strong>Generate</strong>.</li>
        <li>A 16-character App Password will be displayed. Copy and use this password as SMTP password in the GUI application.</li>
      </ul>
    </li>
</div>


---
## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/na-veen8386/image_steganography_tool.git
pip install pillow cryptography secure-smtplib
cd image-steganography




