# CLI / Bash Practice – Operation wise Commands

Ye table tumhe clearly dikhayega ki **same operation** har OS me kaise perform hota hai.

| Operation | Linux / macOS (Bash) | Windows (PowerShell / CMD) |
|-----------|----------------------|----------------------------|
| Current location | `pwd` | `cd` |
| List files | `ls` | `dir` |
| Change directory | `cd folder` | `cd folder` |
| Create folder | `mkdir test` | `mkdir test` |
| Create file | `touch a.txt` | `New-Item a.txt` |
| Delete file | `rm a.txt` | `del a.txt` |
| Delete folder | `rm -r test` | `rmdir /s test` |
| Copy file | `cp a b` | `copy a b` |
| Move / Rename | `mv a b` | `move a b` |
| Clear screen | `clear` | `cls` |

---
### Important Note
- **AWS EC2 / Ubuntu server → Bash commands use hote hain**
- Windows commands sirf local Windows ke liye hote hain
- Concepts same rehte hain, commands thodi different hoti hain

Agar chaho to next step me isko **advanced bash + server real examples** ke sath upgrade kar sakte hain.

---
## 🔐 Permissions & Ownership (Backend / Cloud ke liye MUST)
| Operation | Linux / Ubuntu Command |
|-----------|------------------------|
| Check permissions | `ls -l` |
| Change permission | `chmod 755 file` |
| Change owner | `chown user:group file` |
| Run as root | `sudo command` |

---
## ⚙️ Process & System Monitoring
| Operation | Command |
|-----------|---------|
| Running processes | `ps aux` |
| Live process monitor | `top` , `htop` |
| Kill process | `kill PID` , `kill -9 PID` |
| System uptime | `uptime` |
| Memory usage | `free -h` |
| Disk usage | `df -h` , `du -sh folder` |

---
## 🌐 Networking (Backend + Cloud Core)
| Operation | Command |
|-----------|---------|
| Check IP address | `ip a` |
| Test connectivity | `ping google.com` |
| Check open ports | `ss -tuln` , `netstat -tuln` |
| HTTP request / API test | `curl url` |
| Download file | `wget url` |
| DNS lookup | `nslookup domain` |

---
## 📦 Package Management (Ubuntu / EC2)
| Operation | Command |
|-----------|---------|
| Update package list | `sudo apt update` |
| Upgrade packages | `sudo apt upgrade` |
| Install package | `sudo apt install nginx` |
| Remove package | `sudo apt remove nginx` |

---
## 🚀 Service & Server Management
| Operation | Command |
|-----------|---------|
| Start service | `sudo systemctl start nginx` |
| Stop service | `sudo systemctl stop nginx` |
| Restart service | `sudo systemctl restart nginx` |
| Service status | `sudo systemctl status nginx` |
| View logs | `journalctl -u nginx` , `tail -f logfile` |

---
## ☁️ Cloud / Remote Operations (VERY IMPORTANT)
| Operation | Command |
|-----------|---------|
| SSH into server | `ssh user@ip` |
| Copy file to server | `scp file user@ip:/path` |
| Copy folder to server | `scp -r folder user@ip:/path` |
| Check env variables | `env` |
| Set env variable | `export KEY=value` |
| Command history | `history` |
| Clear terminal | `clear` |

---
### 🔥 Reality Check (Backend / Cloud)
- **Production servers Linux-based hote hain**
- GUI almost kabhi nahi hota
- Ye commands aati hain → tum real server handle kar sakte ho
- AWS, Azure, GCP → sab jagah yehi kaam aata hai

