# 🏴‍☠️ Bandit Level 3 → Level 4

## 🎯 Objective
Find the password for the next level (**bandit4**).  
The password is stored in a hidden file inside the `inhere` directory.

---

## 🔧 Steps Taken

1. **Connect to the server as bandit3:**
   ```bash
   ssh bandit3@bandit.labs.overthewire.org -p 2220
   Password used: (from Level 2 → 3).
2. **List the files in the home directory:**
   ls
   Output:
   inhere
3. **Enter the directory:**
   cd inhere
4. **Reveal hidden files using -a:**
   ls -a
   Output:
   .  ..  ...Hiding-From-You
5. **Read the hidden file:**
   cat ...Hiding-From-You
## 📸Evidence
![screenshot](./screenshots/level3-4.png)
   
