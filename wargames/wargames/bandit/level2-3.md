# 🏴‍☠️ Bandit Level 2 → Level 3

## 🎯 Objective
Find the password for the next level (**bandit3**).  
The password is stored in a file called **spaces in this filename** located in the home directory.

---

## 🔧 Steps Taken

1. **Connect to the server as bandit2:**
   ```bash
   ssh bandit2@bandit.labs.overthewire.org -p 2220
Password used: (from Level 1 → 2).

2. **List the files in the home directory:**
ls
Output: --spaces in this filename--

3. **Problem:**
The file contains spaces in its name.
It also starts with --, so Linux interprets it as a command option.

4. **Solutions:**
Using quotes:
cat "./--spaces in this filename--"
Using escape characters:
cat ./--spaces\ in\ this\ filename--

## 📸Evidence
