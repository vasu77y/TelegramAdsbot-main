# 🤖 TelegramAdsBot

A powerful **Telegram Ads Automation Bot** built using Python and Pyrogram.
Designed to demonstrate automation workflows, multi-account handling, and campaign-based messaging systems.

> ⚠️ **IMPORTANT DISCLAIMER**
> This project is a **testing & educational version only**.
> It is created to show how Python Telegram bots work.
> ❌ Not for production
> ❌ Not for spam/misuse
> ✔ For learning & research purposes only

---

## 🚀 Features

### 👤 User Features

* 📱 Flexible phone login (ANY format supported)
* 🔑 OTP auto-detection (spaces, dashes, pasted formats)
* 👥 Multi-account management
* 🎯 Group targeting system
* 📝 Custom ad message system
* 🔄 Multi-round campaign automation
* 📊 Live stats & analytics

---

### ⚙️ Automation System

* 🔄 Auto message broadcasting
* 🛡️ Anti-flood protection
* ⏱️ Delay + interval control
* 📈 Campaign tracking system
* 🧠 Smart group fetching

---

### 🔒 Security & Control

* Force join system
* Maintenance mode
* Ban system
* Rate limiting
* Session handling

---

### 🛠 Admin Panel

* 👑 Full admin control
* 🔒 Force join channel setup
* 🚫 Ban / unban users
* 📊 Bot statistics
* ⚙️ System settings control
* 📝 Admin logs

---

## 📁 Project Type

This bot is:

* ✔ Fully asynchronous (asyncio based)
* ✔ Built with **Pyrogram**
* ✔ JSON-based database system
* ✔ Single-file architecture (can be modularized)

---

## ⚙️ Configuration

The bot uses **environment variables**:

```env
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
ADMIN_IDS=123456789
```

---

## 📦 Installation

### 1. Clone Repo

```bash
git clone https://github.com/vanshcz/TelegramAdsBot.git
cd TelegramAdsBot
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

If missing:

```bash
pip install pyrogram tgcrypto phonenumbers dnspython
```

---

## ▶️ Run Bot

```bash
python main.py
```

---

## 🧠 How It Works

1. User logs in using phone number
2. Bot sends OTP via Telegram
3. Session is stored securely
4. User selects:

   * Accounts
   * Targets
   * Message
   * Settings
5. Bot launches automated campaign 🚀

---

## 📊 Plans System

* 🆓 Free → Limited usage
* ⚡ Basic → More accounts
* 💎 Pro → High limits
* 👑 Elite → Unlimited access

---

## 🔒 Force Join

Users must join a channel before using the bot.

Set inside settings:

```json
"force_join_channel": "@yourchannel"
```

---

## ⚠️ Warning

This bot can interact with Telegram groups and accounts.

You MUST:

* Follow Telegram Terms of Service
* Avoid spam or abuse
* Use only for testing/learning

---

## 👨‍💻 Developer

**Vansh** 🚀

* 🌐 Website: https://vanshcz.online
* 📺 YouTube: https://youtube.com/@vanshcz
* 📸 Instagram: https://instagram.com/vanshcz
* 💬 Telegram: https://t.me/skullmoddder
* 🤖 Channel: https://t.me/botsarefather
* 🐙 GitHub: https://github.com/vanshcz

---

## 📌 Credits

Developed & launched by **Vansh**
For **educational purposes only** 🎓

---

## ⚖️ Disclaimer

This project is strictly for:

✔ Learning
✔ Testing
✔ Educational understanding

❌ The developer is NOT responsible for misuse.

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 📢 Share it

---
