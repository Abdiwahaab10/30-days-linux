
# 🐧 Day 01 – Linux Fundamentals

## 📌 Overview

Linux is a **free and open-source operating system** used to manage computers, servers, and cloud systems.

It is widely used in:

* 🌐 Web servers
* 🔐 Cybersecurity
* ☁️ Cloud computing
* 📡 Networking systems

---

## 🧠 What Makes Linux Special?

* Open-source (free to use & modify)
* Highly secure
* Lightweight and fast
* Used in 90% of servers worldwide

---

## 🏗️ Linux Architecture

```
User
 ↓
Shell (Bash)
 ↓
Kernel
 ↓
Hardware
```

### Key idea:

* **Kernel** → Core of Linux (controls everything)
* **Shell** → Interface where you type commands

---

## 📁 Linux File System Basics

| Directory | Purpose               |
| --------- | --------------------- |
| `/`       | Root (main directory) |
| `/home`   | User personal files   |
| `/etc`    | System configuration  |
| `/var`    | Logs and system data  |
| `/bin`    | Essential commands    |
| `/usr`    | Installed software    |

---

## 💻 Basic Linux Commands

### 📍 Navigation

```bash
pwd        # show current location
ls         # list files
cd folder  # enter folder
cd ..      # go back
```

---

### 📁 File Management

```bash
touch file.txt     # create file
mkdir folder       # create folder
cp a b             # copy file
mv a b             # move or rename
rm file.txt        # delete file
rm -r folder       # delete folder
```

---

### 📄 View Files

```bash
cat file.txt       # show content
less file.txt      # scroll content
head file.txt      # first lines
tail file.txt      # last lines
```

---



## 🧪 PRACTICAL LAB (Day 01)

### 🎯 Task:

1. Create a folder:

```bash
mkdir linux-day1
```

2. Enter folder:

```bash
cd linux-day1
```

3. Create files:

```bash
touch notes.txt commands.txt
```

4. Write into file:

```bash
echo "Linux Day 01 Notes" > notes.txt
```

5. View file:

```bash
cat notes.txt
```

---

## 📊 GitHub Folder Structure

```
Linux-Fundamentals/
│
├── Day-01/
│   ├── notes.md
│   ├── commands.md
│   └── lab.md
```

---

## 🚀 Summary

Today you learned:

* What Linux is
* Basic architecture
* File system structure
* Essential commands
* Simple lab practice

---

## 🔥 Challenge

Try this without looking:

* Create 3 folders
* Inside each folder create 2 files
* Delete one file using terminal

---


