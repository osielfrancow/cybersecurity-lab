# 🏴‍☠️ Bandit Level 0 → Level 1

## 🎯 Objective
Connect to the **OverTheWire Bandit server** via SSH and retrieve the password for Level 1.

---

## 🔧 Steps Taken

1. **Open the terminal (Ubuntu VM):**
   ```bash
   ssh bandit0@bandit.labs.overthewire.org -p 2220
   
bandit0 → Initial username
bandit.labs.overthewire.org → Remote server
-p 2220 → Custom SSH port
Enter the password provided by OverTheWire for bandit0.

List files in the home directory:
ls
Output: readme

Read the file to obtain the Level 1 password:
cat readme
Output: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## 📸 Evidence
![Bandit Level 0 to 1 Screenshot](Level%200%20Bandit%20.png)

