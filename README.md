# password_cracker-in-Java
It's a compressed-file password cracker ONLY FOR EDUCATIONAL PURPOSES using netbeans (JAVA Maven)as GUI zip4j-2.11.5.jar dependency using Bruteforce approach 


# Password Cracker in Java

A **Java-based password cracker** built as a practice project for academic purposes.  
It can crack **ZIP files** using brute-force or dictionary methods, and has planned modular support for **RAR** and **7Z** files.

---

## Features
- **Formats Supported:**  
  - `.zip` (using Zip4j) – working  
  - `.rar` (planned using Junrar / unrar.exe)  
  - `.7z` (planned using 7z.exe)
- **Multithreaded brute-force engine** for faster cracking.
- **Charset and length customization** for password guesses.
- **CRC validation** to ensure correctness.
- **NetBeans GUI** – interactive buttons, progress display.
- **Modular design** – future expansion to multiple archive types.

---

## Technologies Used
- **Java 17+**
- **NetBeans IDE**
- **Zip4j Library**
- **Multithreading, OOP, JDBC**
- **Planned integrations:** Junrar, 7-Zip CLI

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/crimsoman/password_cracker-in-Java.git

