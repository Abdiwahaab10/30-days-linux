

# 🐧 Day 01 – Linux Basic Commands

## 📌 1. Navigation Commands

These commands help you move around the Linux file system.

```bash id="nav1"
pwd
```

👉 Show current directory (where you are now)

```bash id="nav2"
ls
```

👉 List files and folders in current directory

```bash id="nav3"
cd folder_name
```

👉 Move into a specific folder

```bash id="nav4"
cd ..
```

👉 Go back one level (parent directory)

```bash id="nav5"
cd ~
```

👉 Go to home directory

---

## 📁 2. File Management Commands

These commands are used to create, copy, move, and delete files/folders.

### 📄 Create Files & Folders

```bash id="file1"
touch file.txt
```

👉 Create a new empty file

```bash id="file2"
mkdir folder_name
```

👉 Create a new folder

---

### 📋 Copy & Move

```bash id="file3"
cp file1.txt file2.txt
```

👉 Copy a file

```bash id="file4"
mv file1.txt newname.txt
```

👉 Rename a file

```bash id="file5"
mv file.txt folder_name/
```

👉 Move file into a folder

---

### ❌ Delete

```bash id="file6"
rm file.txt
```

👉 Delete a file

```bash id="file7"
rm -r folder_name
```

👉 Delete a folder (recursive)

---

## 🔐 3. Basic System Info Commands

These commands show system and user information.

```bash id="sys1"
whoami
```

👉 Show current logged-in user

```bash id="sys2"
id
```

👉 Show user ID and group information

```bash id="sys3"
uname -a
```

👉 Show system details (kernel, OS info)

```bash id="sys4"
hostname
```

👉 Show computer name

---

## 🚀 Summary

Today you learned:

* 📍 How to navigate Linux system
* 📁 How to manage files and folders
* 🔐 How to check basic system information

---

## 🧠 Practice Challenge

Try this:

```bash id="practice1"
mkdir mylab
cd mylab
touch test.txt
echo "Hello Linux" > test.txt
cat test.txt
```

---

