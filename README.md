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

## **Usage**
```sh
C:\temp\projects>Hyrollon.exe


------------------------Hyrollon----------------------------

MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWNXOddKMMMWWX0K0xdl;c0
MMMMMMMMMMMMMMMMMMWXOxdodkKWMWWNX0Oxxxxkkdcl0XXXK0dldl;;'..o
MMMMMMMMMMMMMMMMMNd'..',:;lXWNKOdolcoxxokkdolcc;,'......'';d
MMMMMMMMMMMMMMMMMO'  ..lkdooodxolc;::;'.......,;:lodxO0KXNNW
MMMMMMMMMMMMMMMMMXl.  .:xodkxc;;,...';:c:;,.,o0NWMMMMMMMMMMM
MMMMMMMMMMMMMMMMMWO:',,...oNWNXXK00KXNWWx:;,.'kMMMMMMMMMMMMM
MMMMMMMMMMMMMMWXOdloc,;...dNMMMMMMMMMMMMKc'''lXMMMMMMMMMMMMM
MMMMMMMMMMMMWKkkkkxk0xc;.:OWMMMMMMMMMMMMWk:.,OWMMMMMMMMMMMM
MMMMMMMMMMMMKdkNWXOdOXkc::lKWMMMMMMMWXOdl'...:OWMMMMMMMMMMMM
MMMMMMMMMMMNdoXWXdxkox0d,.;lkXWMMMMN0d;;o; .'lKWMMMMMMMMMMMM
MMMMMMMMMMWklONXd';O0ddxl'';,;ok0Oo;,,cOk;..:okXWMMMMMMMMMMM
MMMMMMMMMM0llO0x' ,xXNk:c;','   .    'xO'.....'dNMMMMMMMMMMM
MMMMMMMMMNo';okl. .cOWXdc;'',.    .,lOXk. . ...cXMMMMMMMMMMM
MMMMMMMMMNl..c00l..'oKWN0l'.:c::cdONMMNc  .',;''kWMMMMMMMMMM
MMMMMMMMMMXo..:kK0o,'dXWNx'.:ONWMMMMMWx..,';cdo.:KMMMMMMMMMM
MMMMMMMMMMMW0l..,lolox0WNx..;OXNMMMMMK:.:o;:cd0:.dNMMMMMMMMM
MMMMMMMMMMMMMK;   .c0KKNWd. ,kKNMMMMWd'.cd:clxNk.,OWMMMMMMMM
MMMMMMMMMMMMMk.   .c0XXNXo. 'x0XMMMM0:';odcclxNNl.lXMMMMMMMM
MMMMMMMMMMMMNl    .o0NNXKl  .oOXMMMNo,loddl::dNM0;'kWMMMMMMM
MMMMMMMMMMMMO'  ..;xKWXKKc  .oOXMMMO;cxxdl,..c0WWx.:KMMMMMMM
MMMMMMMMMMMNc  .,lkKNWKOk;  .lkKMMXl;xOxdl:.'cKWMXc'dNMMMMMM
MMMMMMMMMMWk.  .:xOKKX0Ok,  .ckKMWx,lKOdoxd::dXMMMO,;0WMMMMM
MMMMMMMMMMNc  .'cdkOkkk0x'   cxKWK:;OXkdokx'.lXMMMNo'lXMMMMM
MMMMMMMMMMO'  .':dkkxloOx'   :xKNo,dNXxooOO. cXMMMMK:'kWMMMM
MMMMMMMMMWd.   .;ldxl:lxd.   ;dkd,,ldo::cdd,.,oxkkkkc'c0WMMM
MMMMMMMMMNl.   .':oo;';oo.   ;od;.:ol;.';ld:.,ccc:::;,'oXMMM
MMMMMMMMMMXkdo:...,,...:c:cc;lxl,:KWNo,;dXNOdKMWWWWWNO;;OWMM
MMMMMWX0KNMMMMO'   ..   'xWMW0kc:0WMK:.:OMMWWWMMMMMMMWx,lXMM
MMM0l:,;;lO0KNx.  .;,   ;0MMWd';xNMMXc.:KMMMMMMMMMMMMMXl,kNM
MMWo      '',Od. .'l:  .:0MM0;.cXMMMK:'dNMMMMMMMMMMMMMWO::0M
MMWo.     ...xo. .;xc  .:ONXo;lkNWWWK:'xXXXXXKKKKKXNNWWWO:xW
MWNo      ...ll  'lo,  .,lxo;lxkO000k;;dOOOOOOkOOO000KKXXxlK
Kxl'      ...,'  ';,.   .';''clccccl:',cloxk00K0000000KKX0od
Ol,......... ..  .,..''..''';cccccldc'cdodxkkkkkxddddoddxdoo
NKOkxdl:;:cclllc::cox00kxoc:;;:::coOl;x0OOKKKXXXKKKKKKXXXXXN
MMWWWNK0O0KKKXXXKK0O0K0Okxxxxddolc::;ck0OO0KXK00KXXKKXNNXNWM
MMMMMMMWMMMMMMMWNNNXXXNNKOO0XXXK000OkkOO0XXNNXK00KWMMMMMMMMM

------------------------Hyrollon----------------------------


Description: Hyrollon is a local enumeration and suggestion tool designed to analyze
             and provide relevant options or recommendations within a specific context.

Usage: Hyrollon@Terminal# help  [List all the top commands]
       Hyrollon@Terminal# list  [List all the features commands]

Hyrollon@Terminal# help
1. help
2. list
3. exit

Hyrollon@Terminal# list
1. BITS
2. Registry
3. LocalEnum
4. Services

Hyrollon@Terminal# BITS

Hyrollon@Terminal (BITS Jobs)# exit
[x] Exiting Bits Jobs......

Hyrollon@Terminal# Registry

Hyrollon@Terminal (Registry)# exit
[x] Exiting Registry......

Hyrollon@Terminal# Services

Hyrollon@Terminal (Services)# help
1. help
2. list
3. enum
4. view
5. options
6. attack
7. exit

Hyrollon@Terminal (Services)# options
------------------ Set Options ----------------
serviceName                     [Name of the service, e.g. set serviceName MyService]
displayName                     [Describing name, e.g. set displayName reverse_shell]
exePath                 [Executable file path, e.g. set exePath C:\Temp\reverseShell.exe]

Hyrollon@Terminal (Services)# attack

[i] Enter commands to set parameters (e.g., 'set serviceName <Service_Name>, set displayName <display name>, set exePath <path_of_executable>'):
[i] Type 'run' to create/modify and start the Service.

Hyrollon@Terminal (Services)> Attack# exit
[+] Exiting attack mode...

Hyrollon@Terminal (Services)# exit
[x] Exiting Services...

Hyrollon@Terminal# exit
[x] Exiting......
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