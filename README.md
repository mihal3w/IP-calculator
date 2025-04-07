🧠 IP Calculator & Network Planning Tool

An intuitive desktop application that combines **IP network parameter calculations** with **automated subnet allocation** for different physical or logical locations (e.g., departments, offices, floors).

Built with Python and a `tkinter`-based graphical user interface.

---

## 🚀 Key Features

### ✅ IP Calculator
- Calculates:
  - Subnet mask
  - Wildcard mask
  - Network and broadcast addresses
  - First and last usable host
  - Total number of hosts
- Converts IP address and subnet mask to binary format
- Clean and interactive GUI for easy input and result display

### 🗂️ Subnet Distribution
- Automatically splits a given network (e.g., `192.168.0.0/24`) according to the needs of different locations
- Allows entry of a list of locations and required number of hosts for each
- Generates subnets with:
  - Optimal address space utilization
  - Details such as network address, broadcast, first/last host, subnet mask, etc.
- Option to expand each result for more detailed view

---

## 🛠️ Built With

- **Python 3**
- **Tkinter** – graphical user interface
- **ipaddress** – IP and network calculations
- **ttk** – styled GUI components

---

## 📥 Getting Started

1. Make sure you have Python 3 installed:
```bash
python --version

git clone https://github.com/михал3в/ip-calculator.git
cd ip-calculator
python ip_calculator.py

