# Umbra Privacy Auto Bot 🚀

This Python script empowers you to interact seamlessly with the Umbra Privacy platform, automating the email verification and referral redemption process.

🔗 Register: [Umbra Privacy](https://app.umbraprivacy.com/?ref=ECQJGX)

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Creates multiple accounts with automatic referral redemption.
- **Central Menu System**: Interactive menu for easy script selection via `umbra_main.py`.
- **Colorful CLI**: Uses `colorama` for visually appealing output with colored text and borders.
- **Asynchronous Execution**: Built with `asyncio` for efficient API interactions.
- **Error Handling**: Comprehensive error catching for API requests and OTP retrieval.
- **Bilingual Support**: Supports both English and Vietnamese output based on user selection.
- **Proxy Support**: Supports HTTP, HTTPS, and SOCKS5 proxies for network requests.

### Included Features

✨ **Automated Email Verification** (`autoreff.py`)

- ✅ Temporary email generation using otpmail.vn
- ✅ Automatic domain selection from available domains
- ✅ Email expiration tracking
- ✅ Multi-threading support for multiple accounts

✨ **OTP Retrieval & Verification**

- ✅ Automatic OTP code retrieval from email inbox
- ✅ Real-time inbox polling
- ✅ OTP code extraction and verification
- ✅ Retry mechanism for failed OTP retrieval

✨ **Referral Code Redemption**

- ✅ Automatic referral code redemption
- ✅ Account state tracking
- ✅ Points and referral count display
- ✅ Global rank and waitlist position

✨ **Display Handle Customization**

- ✅ Optional custom display handle setting
- ✅ Handle availability checking
- ✅ Account profile customization

✨ **Proxy Support**

- ✅ HTTP/HTTPS proxy support
- ✅ SOCKS4/SOCKS5 proxy support
- ✅ Proxy authentication support
- ✅ IP address verification

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- Python 3.8+
- `pip` (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt` (ensure `aiohttp`, `aiohttp-socks`, `colorama`, and `inquirer` are included).
- **proxies.txt** (optional): Add proxy addresses for network requests, if needed.

## 📦 Installation

1. **Clone this repository:**
   ```sh
   git clone https://github.com/thog9/Umbraprivacy-waitlist.git
   cd Umbraprivacy-waitlist
   ```
2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Prepare Proxy File (optional):**
   - Create `proxies.txt` for specific operations:
   ```sh
   nano proxies.txt
   ```
   Format: `ip:port:user:pass` (one per line)
   Example:
   ```
   http://username:password@proxy.com:8080
   socks5://username:password@proxy.com:1080
   ```
4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese/English).
   - Select the script you want to run.

**Language Selection:**
- Choose between Vietnamese (Tiếng Việt) and English
- All scripts support bilingual output

## 📁 Project Structure

```
Umbraprivacy-waitlist/
├── main.py              # Central menu system for Umbra Privacy
├── proxies.txt          # Proxies file (optional)
├── accounts.txt         # Generated accounts (auto-created)
├── requirements.txt     # Python dependencies
├── README.md            # This file
└── scripts/             # Other scripts (Evoevo project)
    └── autoreff.py      # Umbra Privacy auto referral bot

```

## 📊 Output Format

Generated accounts are saved in `accounts.txt` with the following format:
```
Email: xxx@domain.com | Handle: username | Referral: xxxxxx | Token: xxxxxxxxxxxx
```

## 📨 Contact

Connect with us for support or updates:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099) 

----

## ☕ Support Us

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)
