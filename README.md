# Digispark Payloads 🚀

This repository contains a collection of **Digispark (ATTiny85) USB Rubber Ducky style payloads** for educational and penetration testing purposes.  
With these scripts, you can automate keystrokes, run quick commands, and demonstrate how USB-based attacks work.

---

## ⚠️ Disclaimer
These payloads are created **only for educational and ethical purposes**.  
The author is **not responsible** for any misuse. Please use them **only on systems you own or have permission to test**.

---

## 📦 Requirements
- **Digispark USB Development Board (ATTiny85)**
- Arduino IDE installed on your system
- Digispark drivers installed
- Basic knowledge of Arduino programming

##  Install Arduino IDE
- Download from Arduino official website
- Add Digispark Board to Arduino IDE
- Open File → Preferences
- In Additional Board Manager URLs, add:
```bash
http://digistump.com/package_digistump_index.json
https://drazzy.com/package_drazzy.com_index.json
```
- Go to Tools → Board → Boards Manager and install Digistump AVR Boards
- Connect Digispark
- Select board:
- Board: Digispark (Default - 16.5 MHz)
---

## 🔧 Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/sachinpandey7709/Digispark-Payloads.git
   cd Digispark-Payloads
