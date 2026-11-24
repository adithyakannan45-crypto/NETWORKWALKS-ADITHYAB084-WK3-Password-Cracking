# 🔐 Password Cracking Report

### PDF Password Recovery Using Networkwalks Online Tools

**W3-PM2 · Cybersecurity · Networkwalks**

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

![Batch](https://img.shields.io/badge/Batch-B084-blue?style=for-the-badge)

![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)

![Tools](https://img.shields.io/badge/Tools-Networkwalks-orange?style=for-the-badge)

![Purpose](https://img.shields.io/badge/Purpose-Education-orange?style=for-the-badge)

---

## 📋 Report Details

| | |
|---|---|
| 👤 **Pentester** | Adithya Nair |
| 🎓 **Program / Batch** | Cybersecurity & Ethical Hacking Internship, B084-Networkwalks |
| 📦 **Module completed** | W3-PM2 (Password Cracking with Networkwalks Tools) |
| 🎯 **Target** | Password-protected PDF provided for the exercise |
| 💻 **Platform** | Kali Linux |
| ✅ **Permission secured** | Yes, authorized internship exercise |

---

## ⚠️ Disclaimer

**Warning**

All activities were performed using the sample PDF provided for the internship exercise, with permission granted by Networkwalks.

This practical is intended for educational and cybersecurity research purposes only. Password recovery techniques must only be used on files that you own or have explicit permission to test.

---

## 🔭 Overview

This module focused on understanding PDF password protection and recovering passwords using Networkwalks online tools.

The practical involved generating a crackable hash from a password-protected PDF using the Networkwalks Hash Calculator and submitting the generated hash to the Networkwalks Password Cracker.

The recovered password was then used to open the original protected PDF and verify the result.

| **Phase** | **Description** | **Status** |
|---|---|---|
| **1** | Locate the internship sample PDF | ✅ Completed |
| **2** | Generate a PDF hash using Networkwalks Hash Calculator | ✅ Completed |
| **3** | Copy the generated PDF hash | ✅ Completed |
| **4** | Submit the hash to Networkwalks Password Cracker | ✅ Completed |
| **5** | Recover the PDF password | ✅ Completed |
| **6** | Verify the recovered password by opening the PDF | ✅ Completed |

---

## 🧰 Tools Used

| **Tool** | **Purpose** |
|---|---|
| 🐧 Kali Linux | Operating system used for the practical |
| 🌐 Mozilla Firefox | Accessing Networkwalks online tools |
| 📄 My Locked PDF1.pdf | Password-protected internship sample |
| 🔑 Networkwalks Hash Calculator | Generating the PDF hash |
| 🔓 Networkwalks Password Cracker | Attempting password recovery |
| 📦 Oracle VirtualBox | Running the Kali Linux virtual environment |

---

## 🔑 1. Locating the Target PDF

**Target file:** `My Locked PDF1.pdf`

The first step was to locate the password-protected sample PDF provided for the internship exercise.

The file was available in the Downloads directory of Kali Linux.

**Command used:**

```bash
cd ~/Downloads
ls -l "My Locked PDF1.pdf"
```

The command verified that the sample PDF was present and accessible.

**Result:** Successfully located the internship sample PDF.

<img width="1077" height="1517" alt="1000128042" src="https://github.com/user-attachments/assets/e0aeaa46-7836-4a80-b07f-d3106f6dd84b" />


---

## 🧮 2. Generating the PDF Hash

The Networkwalks Hash Calculator was opened using Firefox in Kali Linux.

The password-protected PDF was uploaded to the tool for hash generation.

The tool processed the PDF and generated a hash beginning with:

```text
$pdf$
```

This hash contains information required by compatible password recovery tools to attempt password recovery.

**Tool used:** Networkwalks Hash Calculator





## 📋 3. Copying the Generated Hash

After the hash was generated successfully, the complete hash was selected and copied.

It was important to copy the entire hash without missing any characters because incomplete hash information could prevent the password recovery tool from processing it correctly.

**Result:** Successfully copied the generated PDF hash.

---

## 🔓 4. Password Recovery Using Networkwalks Password Cracker

The Networkwalks Password Cracker was opened in Firefox.

The previously generated PDF hash was entered into the tool, and the password recovery process was started.

The tool processed the submitted hash and attempted to identify the password associated with the protected PDF.

**Tool used:** Networkwalks Password Cracker

<img width="1920" height="982" alt="Screenshot_2026-11-23_23_50_34" src="https://github.com/user-attachments/assets/39b4959f-676d-4e6b-830b-090e1194f2c7" />


---

## 🔐 5. Password Recovered Successfully

After the recovery process completed, the tool displayed the recovered password.

The recovered password was used in the next stage to verify whether the original PDF could be unlocked.

| **Result** | **Status** |
|---|---|
| PDF hash generated | ✅ Successful |
| Hash submitted | ✅ Successful |
| Password recovery | ✅ Successful |
| Password verification | ✅ Successful |

<img width="1920" height="982" alt="Screenshot_2026-11-23_23_54_14" src="https://github.com/user-attachments/assets/30290544-7efa-48bc-a484-0f1c5706e30f" />


---

## 📄 6. Verifying the Recovered Password

The original `My Locked PDF1.pdf` file was opened again.

The recovered password was entered into the PDF password prompt.

The document opened successfully, confirming that the recovered password was correct.

**Final Result:** Successfully unlocked the password-protected internship PDF.
<img width="1058" height="1460" alt="1000128043" src="https://github.com/user-attachments/assets/795a2623-524b-436f-b5c8-ad7c9f0462ac" />


## 🚦 7. Risk Analysis

| **#** | **Finding** | **Evidence** | **Potential Impact** | **Risk** |
|---|---|---|---|---|
| 1 | Weak PDF password | Password recovery was successful | Weak passwords may be recovered through guessing attacks | 🟡 Medium |
| 2 | Password hash exposure | PDF hash generated and copied | Exposed hashes can be used for offline password attacks | 🟡 Medium |
| 3 | Reliance on common passwords | Password recovery completed successfully | Common passwords are easier to guess or recover | 🔴 High |
| 4 | Third-party processing | PDF uploaded to an online tool | Confidential documents may be exposed if uploaded without proper authorization | 🔴 High |

**Note**

PDF password protection depends on the encryption configuration and password strength. Weak passwords can make protected documents vulnerable to password recovery attacks.

---

## ✅ 8. Recommendations

1. 🔐 Use long, strong, and unique passwords for protected PDF documents.
2. 🚫 Avoid common passwords and easily guessable combinations.
3. 🔑 Use a password manager to generate and store secure passwords.
4. 🛡️ Use modern PDF encryption standards, such as AES-256, where supported.
5. 🔒 Never upload confidential or personal documents to unknown online password recovery services.
6. 🔁 Avoid reusing the same password across multiple documents.
7. 🧪 Periodically review the security of password-protected documents.

---

## 🎓 9. What I Learned

Through this practical, I learned:

- How password-protected PDF documents work.
- How to generate a PDF hash using an online Hash Calculator.
- The purpose of PDF hashes in password recovery.
- How to use Networkwalks Password Cracker.
- How password recovery tools process extracted hash information.
- How to verify a recovered password by opening the original document.
- The importance of strong passwords and secure document handling.

---

## 🏁 10. Conclusion

This practical provided hands-on experience with PDF password recovery using Networkwalks online tools.

I successfully located the internship sample PDF, generated its hash using the Networkwalks Hash Calculator, submitted the hash to the Password Cracker, and recovered the password.

The recovered password was then used to open the original PDF successfully.

This exercise improved my understanding of PDF password protection, hash generation, password recovery techniques, and the importance of strong password security.

It also highlighted the need to perform password recovery activities responsibly and only with proper authorization.

---

## 👤 Author

**Adithya Nair**

Cybersecurity & Ethical Hacking Internship · Networkwalks (Batch B084)

---

⭐ *This project was completed as part of the Week 3 practical training in cybersecurity and ethical hacking.*
