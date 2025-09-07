# scanner.py
OSINTHound-PortScanner is a lightweight, beginner-friendly port scanning tool written in pure Python 3. It lets you quickly check a target host for open ports within a given range. No extra libraries, no setup hassle — just clone and run.

# OSINTHound-PortScanner 🔍

A **super simple port scanner** written in **pure Python 3**.  
No dependencies, no setup headaches. Just clone and run.

⚠️ **Important:** Only scan systems you own or have explicit permission to test.

---

## 🚀 Quick Start (copy & paste)

```bash
# 1. Clone repo
git clone https://github.com/your-username/OSINTHound-PortScanner.git
cd OSINTHound-PortScanner

# 2. Run the scanner
python3 scanner.py 127.0.0.1 20-100

EXAMPLE:

$ python3 scanner.py 127.0.0.1 20-100
[+] Scanning 127.0.0.1 ports 20-100 ...
[+] Open ports on 127.0.0.1: [22, 80]

