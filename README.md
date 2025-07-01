
<p align="center">
  <img src="https://i.ibb.co/bgF3J4k1/retouch-2025062617044531.jpg" alt="SPYDRAX Logo" width="300"/>
</p>

# 🕷️ SPYDRAX Shell

**SPYDRAX** is a powerful and advanced PHP web shell designed for penetration testers, red teams, and cyber researchers. It comes with a sleek UI and a comprehensive set of tools for post-exploitation, privilege escalation, and server management.

![Login Page](https://i.ibb.co/4BSJ7nW/IMG-20250626-222910.jpg)
*SPYDRAX Login Interface*

---

## 🚀 Features

- 🖥️ **Terminal**
- 🧨 **Terminal Bypass (TOP)**
- 🧪 **Scanner SUID (TOP)**
- 🔐 **Auto Root (ROOT)**
- 🦠 **Malware Scanner**
- 🚫 **Check Disabled Functions**
- 🗃️ **Database Manager**
- ⚙️ **Process Manager**
- 🌐 **Network Connections Viewer**
- 🗂️ **Adminer Integration**
- 👾 **Backdoor Destroyer**
- 🔒 **Lock Shell / File**
- 👤 **Create User (ROOT)**
- 🖥️ **Create RDP**
- 🧬 **Linux Exploit Tools**
- 📧 **PHP Mailer**
- 🔄 **Backconnect**
- 🔓 **Unlock Shell**
- 🧬 **Hash Identifier**
- 🔁 **CPanel Reset**
- 🌐 **Create WordPress User**

---

## 📂 File Manager

- Browse, upload, delete, rename, and execute files
- See system info, PHP version, IP address, and OS details
- Visual folder navigation

![UI Screenshot](https://i.ibb.co/C3Zc0wCS/IMG-20250626-222848.jpg)
*Main Shell UI with File & Tool Panel*

---

## 🔐 Authentication

The shell is protected by a login screen with password authentication.

- **Default Password:** `khadiza`
- Password is stored as an **MD5 hash** in the source file.
- 🔁 To change it, edit the line containing the MD5 hash in the PHP source:

```php
$hashedPassword = "e9fe3f2a7b5f4d5011e1b9f8e1d1b9d0"; // Replace with your own md5 hash
```

You can generate your own hash using:

```bash
echo -n 'YourNewPassword' | md5sum
```

---

## ⚠️ Disclaimer

This tool is intended **only for educational purposes** and **authorized penetration testing**. The developer is **not responsible** for any misuse or illegal activity done with this script.

---

## 🧑‍💻 Author

**SpydraX**  
GitHub: [thespydrax]  

---
**HaxorSec**  
Github: [unknown]  

## 🙏 Special Thanks

Big thanks to the **HaxorSec Team** for their support and contribution to the security community.

---

## 📜 License

No license. All rights reserved by the author.
