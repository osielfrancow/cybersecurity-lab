# 🏴‍☠️ Bandit Level 1 → Level 2

```bash
# Objective:
# Connect as bandit1 and read the file named "-" to get the Level 2 password.

# Credentials
# user: bandit1
# host: bandit.labs.overthewire.org
# port: 2220
# pass: (from previous level)

# 1) Connect
ssh bandit1@bandit.labs.overthewire.org -p 2220

# 2) List files
ls
# Expected output:
# -

# 3) Read the file named "-" (use ./ so "-" isn't treated as an option)
cat ./-

# Output → Password for Level 2:
# 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
