# 🔍 Digital Forensics Lab Exam Walkthrough

## 🧾 Overview
This is my final lab exam walkthrough for digital forensics using Metasploit, pypykatz, Hashcat, and Docker-based exploitation.

---

## 🛠 Tools Used
- Parrot OS
- vmware workstation
- pypykatz
- Hashcat
- Metasploit Framework
- FTP
- Base64 Decoder

---

## 🔐 Key Info
- Target IP: `172.16.226.128`
- User: `jasoos`
- Password: `Password@1`
- Docker Subnet: `172.17.0.0/24`

---

## ✅ Steps Performed

1. Extracted `lsass.DMP` and dumped credentials using **pypykatz**.
2. Cracked NTLM hash with **Hashcat** using `rockyou.txt`.
3. SSH login with Metasploit `ssh_login` module.
4. Upgraded shell to Meterpreter using `shell_to_meterpreter`.
5. Discovered Docker IP `172.17.0.2` using `ping_sweep`.
6. Scanned and found open **FTP port**.
7. Logged in with **anonymous FTP** and downloaded `saboot.001`.
8. Decoded Base64 to get final flag: `jeenalisagoodgirl`.

---

## 📂 Downloaded File

- File: `saboot.001`
- Decoded Base64: `jeenalisagoodgirl`

---

## 👩‍💻 Submitted By

**Maheen Iftikhar**  
Sir Syed University – Digital Forensics Lab Exam  
