# Linux File Manager (Terminal-Based File Explorer in C++)

## 📌 Project Overview
This project is a **terminal-based File Explorer** developed using **Modern C++** and the `<filesystem>` library.  
It allows users to **navigate directories, list files, create/delete/copy files, and search files** directly from the console.

This project was developed as part of the **Capstone Project** under **Linux OS & LSP**.

---

## ✨ Features

| Command | Description |
|--------|-------------|
| `ls` | List files and directories in the current path |
| `cd <folder>` | Change directory |
| `cd ..` | Go to parent directory |
| `create <filename>` | Create a new empty file |
| `delete <filename>` | Delete a file |
| `copy <source> <destination>` | Copy a file |
| `search <keyword>` | Search files by name |
| `exit` | Exit the application |

---

## 🛠️ Technologies Used
- Programming Language: **C++ (C++17)**
- Library: **<filesystem>**
- Platform: **Linux (Ubuntu / WSL / Any Linux Distro)**

---

## 🚀 How to Run

```bash
g++ src/file_explorer.cpp -o explorer -lstdc++fs
./explorer


🔮 Future Enhancements
🗃️ Add folder creation & deletion commands (mkdir, rmdir)
🕹️ Introduce a menu-based interface for non-command users
📦 Implement file compression support (.zip/.tar)
🌐 Add remote directory access via sockets
🧠 GUI-based version using C++ Qt framework



linux-file-manager/
│
├── src/
│   └── file_explorer.cpp
│
├── README.md
│
└── screenshots

