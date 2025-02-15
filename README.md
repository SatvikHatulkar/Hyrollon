# Hyrollon - Offensive Security Tool

Hyrollon is an **offensive security tool** designed for **penetration testers, red teamers, and security researchers**.  
It provides deep control over Windows system components, allowing professionals to simulate and understand real-world attack scenarios.  

## ⚠️ Disclaimer
**This tool is for educational and research purposes only. Unauthorized use on any system without permission is illegal. Use responsibly.**

---

## 🚀 Features
### 🔹 1. Registry Key Enumeration & Modification
- Enumerate registry keys to identify persistence mechanisms.
- Modify or delete registry keys as part of privilege escalation techniques.

### 🔹 2. Windows Services Enumeration & Modification
- List all running services and analyze their permissions.
- Create, modify, or delete Windows services to test security mechanisms.
- Ability to check and escalate privileges through service misconfigurations.

### 🔹 3. BITS Jobs Creation (Background Intelligent Transfer Service)
- Create **BITS jobs** to simulate stealthy file transfers used by attackers.
- Enumerate existing BITS jobs for forensic investigation.

### 🔹 4. Local Enumeration (Admin Access Only)
- Extract system information such as **sensitive files, user accounts, processes, network details, and system privileges**.
- Identify potential attack vectors in a Windows environment.

---

## 🔧 Installation
### **Prerequisites**
- Windows Operating System (Windows 10/11 or Server)
- Administrator privileges (for certain features)
- x64 Required

### **Build Instructions**
1. Clone the repository:
   ```sh
   git clone https://github.com/SatvikHatulkar/Hyrollon.git
   cd Hyrollon
   ```

### **Upcoming Updates**
- ### Local Enumeration Add-On:
    1. **user accounts, processes, network details, and system privileges** extraction.
    2. **Identify potential attack vectors in a Windows environment.**
- ### Features Seperation:
    1. Features will be categorized **(Enumeration, Privilege Escalation, Persistence, etc)**
    2. Search Feature.
- ### Availability:
    1. **x86(x32) version will be available soon.**
    2. **Hyrollon Debian.**