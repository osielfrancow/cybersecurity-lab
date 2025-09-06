# 🏴‍☠️ Bandit Level 1 → Level 2

## 🎯 Objective
Connect to the **OverTheWire Bandit** server as `bandit1` and retrieve the password for Level 2.

## 🔑 Credentials
- **Username:** bandit1  
- **Host:** bandit.labs.overthewire.org  
- **Port:** 2220  
- **Password:** (from previous level)

## 🔧 Steps Taken

1. **Connect to the server**
   ```bash
   ssh bandit1@bandit.labs.overthewire.org -p 2220
2.**List files**
ls

3.**Read the file named -**
Use ./- so the - isn’t treated as an option.
cat ./-
# Output → Password for Level 2: 
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## 📸Evidence
![Bandit Level 1 → 2](./level1-2.png)
