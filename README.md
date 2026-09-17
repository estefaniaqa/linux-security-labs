# 🐧 Linux Security: File Permissions & Access Control

## 📌 Project Overview

This project demonstrates the use of Linux commands to inspect and manage
file and directory permissions.

The objective was to understand how Linux access controls determine which
users can read, write, or execute files and directories, and how permissions
can be modified according to security requirements.

---

## 🎯 Objectives

- Inspect file and directory permissions
- Identify hidden files
- Interpret Linux permission strings
- Understand owner, group, and other permissions
- Modify file permissions using `chmod`
- Modify permissions on hidden files
- Manage directory permissions

---

## 🛠️ Linux Commands Used

### View file permissions

```bash
ls -l
```

Displays detailed information about files and directories, including
permissions, ownership, file size, and modification date.

### View hidden files

```bash
ls -la
```

The `-a` option displays all files, including hidden files.

### Modify permissions

```bash
chmod
```

The `chmod` command was used to add or remove permissions according to
the security requirements of the exercise.

---

## 🔐 Understanding Linux Permissions

A Linux permission string can look like:

```text
-rwxr--r--
```

The permissions are divided into:

| Section | Meaning |
|---------|---------|
| `-` | File type |
| `rwx` | Owner permissions |
| `r--` | Group permissions |
| `r--` | Other users |

### Permission symbols

- `r` — Read
- `w` — Write
- `x` — Execute
- `-` — Permission not granted

---

## 🛡️ Security Relevance

File permissions are an important Linux security control because they
determine which users and groups can access or modify system resources.

Managing permissions correctly helps prevent unauthorized access to files
and directories.

---

## 🧠 What I Learned

This project helped me understand how Linux manages access control at the
file-system level.

I learned how to inspect permissions using `ls -l` and `ls -la`, interpret
permission strings, and use `chmod` to modify access for owners, groups,
and other users.

I also practiced managing permissions for hidden files and directories.

---

## 🧰 Skills Demonstrated

- Linux Command Line
- File & Directory Permissions
- Access Control
- `chmod`
- `ls`
- Linux Security Fundamentals

---

## 📄 Full Project Report

The complete project documentation, including terminal examples, is available
in this repository:

[📄 View Linux File Permissions Report](reports/linux-file-permissions.pdf)

---

## 🎓 Project Context

This project was completed as part of my cybersecurity training through the
Google Cybersecurity Professional Certificate.

The documentation presented here reflects my practical learning of Linux
permissions and access control.

---

**Author:** Estefanía Quezada  
**Focus:** Junior Cybersecurity Analyst | SOC | Linux Security
