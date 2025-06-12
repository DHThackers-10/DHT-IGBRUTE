# DHT-IGBRUTE

![DHT-BRUTEFORCE](https://img.shields.io/badge/DHT-HACKERS-magenta?style=for-the-badge)

The ultimate **real Instagram brute-force tool** using session, CSRF, threading, and **auto wordlist generation** — made for **educational purposes only**.

---

# 🎯 DHT-IGBRUTE – Brute with Style!

Welcome to DHT-IGBRUTE — a sleek and fully functional Instagram brute-force tool powered by **Python**, **Rich**, and **Pyfiglet**, with real login logic (not simulation) using encoded passwords and CSRF sessions.

This tool is for **ethical hacking demonstrations only**, helping learners understand how brute-forcing works.

---

# ⚠️ Disclaimer

> This tool is made strictly for **educational** and **ethical hacking** purposes.  
> Do **not** use this tool for any unauthorized or malicious activity.  
> Use it only in environments where you have explicit permission.

---

# 🚀 Installation Guide

Fire up your terminal and run:

```bash
apt update && apt upgrade -y
pkg install python git -y
pip install requests rich pyfiglet bs4 faker
git clone https://github.com/DHThackers-10/DHT-IGBRUTE.git
cd DHT-IGBRUTE
python3 dht_igbrut.py
```

---

# 🖥️ Screenshot

> **Sample Brute Output**

![Screenshot_20250612-103632](https://github.com/user-attachments/assets/e51fbcb4-a173-4300-a33b-2925834d5184)


---

# ⚙️ How It Works

✅ **Real Instagram login request** using:
- `enc_password` format
- CSRF token
- XHR headers

✅ Supports:
- Manual wordlist
- Auto wordlist (smart patterns based on username)

✅ Handles:
- Success ✅
- 2FA Checkpoint 🔐
- Failures ✘
- Rate Limits ⏳

✅ Features:
- Multi-threaded speed
- Timestamped logging
- Google-style terminal design (with `rich`)
- Saved credentials in `found.txt`

---

# 🔧 Options & Flow

1. Enter Instagram username  
2. Choose wordlist mode:
   - Auto generate smart list
   - Load from file
3. Set thread count (recommended: 3-10)
4. Starts brute-force with full session logic
5. Prints live results (success, fail, 2FA)
6. Logs found password to `found.txt`

---

# 📂 Output Example

> `found.txt`
```
dht_hacker : dht786123 (SUCCESS) - 2025-06-12 04:15:21
```

---

# ✅ Features

- ⚡ Fast & Real Attack  
- 🎯 Auto & Manual Wordlist  
- 🧠 Smart Permutations  
- 🎨 Styled with Rich UI  
- 🧾 JSON-style timestamp logs  
- 🔒 2FA Detection  
- 🧵 Threading Support  
- 🧠 Faker User-Agent Rotation  
- ✅ Tested & Working

---

# 🌐 Educational Use Only

**DHT-IGBRUTE** is intended to **educate and raise awareness** about account security and password strength.

Always get permission before testing.

---

# 👨‍💻 Credits

**Created by:** DHT Hackers Team  
**GitHub:** [DHThackers-10](https://github.com/DHThackers-10)  
**YouTube:** [DHT Hackers](https://youtube.com/@dht-hackers_10)  
**WhatsApp Community:** [Join Group](https://chat.whatsapp.com/G2hCkCzylra2OENEfhH8Os)

---

# 💡 Tip

💬 Want more powerful tools?  
Check out `DHT-TRACKER`, `DHT-PHISHER`, `DHT-BRUTXGMAIL`, and more on our GitHub!
