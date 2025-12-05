## 🐧 Linux Commands Cheat Sheet

### 📂 File & Directory Management

| Command                 | Description                   | Use Case                      |
| ----------------------- | ----------------------------- | ----------------------------- |
| `ls`                    | List files                    | See files in current folder   |
| `ls -l`                 | Long listing with permissions | Check file size, date, owner  |
| `ls -a`                 | Show hidden files             | View `.env`, `.gitignore`     |
| `pwd`                   | Show current directory path   | Know where you are            |
| `cd <folder>`           | Change directory              | Navigate into folder          |
| `cd ..`                 | Go up 1 directory             | Move backward                 |
| `cd /path/to/folder`    | Jump to path                  | Navigate anywhere             |
| `mkdir <folder>`        | Create folder                 | Make new project directory    |
| `rmdir <folder>`        | Remove empty folder           | Delete unused directory       |
| `rm -r <folder>`        | Remove folder with files      | Delete folder safely          |
| `touch <file>`          | Create empty file             | Create `app.js`, `.env`, etc. |
| `cat <file>`            | View file content             | Quickly read file             |
| `nano <file>`           | Edit file in terminal         | Edit config files             |
| `cp file1 file2`        | Copy file                     | Make backup copy              |
| `cp -r folder1 folder2` | Copy folder                   | Duplicate project folder      |
| `mv file1 file2`        | Move/Rename file              | Rename/move files             |
| `rm <file>`             | Delete file                   | Remove logs, temp files       |
| `rm -f <file>`          | Force delete                  | Delete without confirmation   |

---

### 🔍 Search Commands

| Command                       | Description                |
| ----------------------------- | -------------------------- |
| `find /path -name "file.txt"` | Search for a file anywhere |
| `find . -type f -name "*.js"` | List all JS files          |
| `grep "text" filename`        | Find text inside file      |
| `grep -R "function" .`        | Recursive search in folder |
| `grep -i "error" log.txt`     | Case-insensitive search    |

---

### 🔐 Permissions & Ownership

| Command                     | Description             |
| --------------------------- | ----------------------- |
| `chmod 755 file`            | Change file permissions |
| `chmod +x file.sh`          | Make script executable  |
| `chown user:user file`      | Change owner of a file  |
| `chown -R user:user folder` | Change folder owner     |

---

### 🖥️ System Information

| Command         | Description             |
| --------------- | ----------------------- |
| `uname -a`      | Full system information |
| `hostname`      | Show machine name       |
| `top`           | Show running processes  |
| `htop`          | Better process manager  |
| `df -h`         | Disk space usage        |
| `du -sh folder` | Check folder size       |
| `free -h`       | Show RAM usage          |
| `uptime`        | Show system uptime      |

---

### 🌐 Network Commands

| Command             | Description                    |
| ------------------- | ------------------------------ |
| `ifconfig` / `ip a` | View IP address                |
| `ping google.com`   | Test network connection        |
| `curl <url>`        | Fetch data from a server       |
| `wget <url>`        | Download files                 |
| `netstat -tulpn`    | Check open ports               |
| `ss -tulpn`         | Modern replacement for netstat |
