
# 🖥️ System Process Logger

A Python-based automation tool that monitors and logs all running system processes at regular intervals.  
It captures details such as **Process ID (PID)**, process name, username, and memory usage, and stores them in timestamped log files for later analysis.  

---

## 🚀 Features
- Tracks all active system processes (PID, name, user, memory usage).  
- Creates **timestamped `.log` files** for historical analysis.  
- Automated logging at user-defined time intervals using `schedule`.  
- Lightweight alternative to Task Manager or `top` command.  
- Helps in **performance monitoring, debugging, and detecting unauthorized processes**.  

---

## 🛠️ Tech Stack
- **Python**  
- `psutil` → for process details  
- `schedule` → for task scheduling  
- `os`, `time` → for file handling and timestamping  

---

## 📂 Project Structure
