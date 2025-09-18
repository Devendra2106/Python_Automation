# Process Mon - Process Monitor

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![psutil](https://img.shields.io/badge/dependency-psutil-green.svg)](https://pypi.org/project/psutil/)

**Process Mon** (*Process Monitor*) is a lightweight Python tool to monitor running processes and generate detailed log files with timestamped filenames. It helps in auditing, debugging, and analyzing system activity.

---

## ✨ Features

* 🔍 Scan all running processes with:

  * Process ID (PID)
  * Process Name
  * Username
  * Virtual Memory Size (in MB)
* 🗂️ Generate timestamped log files automatically.
* 📁 Store logs in a dedicated `Process MonLogs` directory.
* ⚡ Works on Windows, Linux, and macOS.

---

## 🛠️ Requirements

* Python 3.7+
* psutil library

Install dependencies:

```bash
pip install psutil
```

---

## 🚀 Usage

Run the script:

```bash
python Process Mon.py
```

A new log file will be created in the `Process MonLogs` folder.

Example log file name:

```
Process Mon_ThuSep18_2025_17_45_23.log
```

---

## 📄 Example Log Output

```
--------------------------------------------------------------------------------
        Process Mon - Process Log
        Log File created at: Thu Sep 18 17:45:23 2025
--------------------------------------------------------------------------------

{'pid': 1234, 'name': 'python.exe', 'username': 'Om', 'vms': 55.81}
{'pid': 5678, 'name': 'chrome.exe', 'username': 'Om', 'vms': 220.12}

--------------------------------------------------------------------------------
```

---

## 📂 Project Structure

```
.
├── Process Mon.py          # Main script
├── README.md           # Documentation
└── Process MonLogs/        # Auto-generated log files
```

---

## 🧑‍💻 Development

Clone the repository:

```bash
git clone https://github.com/your-username/Process Mon.git
cd Process Mon
```

Run locally:

```bash
python Process Mon.py
```

---

## 🤝 Contributing

Contributions are welcome!

* Open an [issue](https://github.com/your-username/Process Mon/issues)
* Submit a [pull request](https://github.com/your-username/Process Mon/pulls)

---


---

## 👨‍💻 Author

Developed by **Devendra Santosh Deshmukh**
📧 Contact: devendradeshmukh00@gmail
(mailto:your.devendradeshmukh00@gmail.com)
