
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
SystemProcessLogger/
│── process_logger.py # Main script
│── logs/ # Generated log files (after running the script)
│── README.md # Documentation


---

## ⚙️ Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/SystemProcessLogger.git
   cd SystemProcessLogger


Install dependencies:

pip install psutil schedule


Run the script:

python process_logger.py


Provide:

Folder name (where logs should be saved)

Time interval in minutes for logging

Example:

Enter folder name: logs
Enter time interval (in minutes): 2

📊 Sample Log Output
--------------------------------------------------------------------------------
        Marvellous Infosystems Process Log
        Log file is created at : Tue Sep 17 21:15:02 2025
--------------------------------------------------------------------------------
{'pid': 1234, 'name': 'chrome.exe', 'username': 'User', 'vms': 512.0}  

{'pid': 5678, 'name': 'python.exe', 'username': 'User', 'vms': 256.5}  
--------------------------------------------------------------------------------
