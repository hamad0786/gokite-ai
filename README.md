# Kite AI Auto-Bot

An automated interaction bot for the Kite AI platform with multi-wallet and proxy support.

## 🚀 Features

- **Multiple Wallet Support** (manual input or file-based)
- **Proxy Support** (HTTP/HTTPS/SOCKS)
- **Rate Limiting and Retry Mechanisms**
- **Multiple AI Agents Interaction**
- **Automatic Question Selection**
- **Usage Reporting**
- **Graceful Error Handling**
- **Daily Limit: 30 Questions per Wallet (Auto-Reset in 24 Hours)**
- **Message Delay: 5 Minutes Between Each Question**

## 📋 Prerequisites

- **Node.js** (v16 or higher)
- **npm** (Node Package Manager)

## 🛠️ Installation

1. **Clone the repository:**

```sh
git clone https://github.com/hamad0786/gokite-ai
cd gokite-ai
```

2. **Install dependencies:**

```sh
npm install
```

## 📝 Configuration

### 1. Create a `questions.json` file with your questions:

```json
[
  "What is cryptocurrency?",
  "How does Bitcoin work?",
  "What is Ethereum?",
  "How are NFTs related to blockchain?",
  "What is DeFi (Decentralized Finance)?",
  "How does a blockchain transaction work?",
  "What are the benefits of blockchain technology?",
  "What is a private blockchain?",
  "How does proof-of-work (PoW) differ from proof-of-stake (PoS)?",
  "What is a crypto wallet?"
]
```

### 2. (Optional) Create a `proxies.txt` file for proxy support:

```sh
http://user:pass@host:port
socks5://user:pass@host:port
```

### 3. Create a `wallets.txt` file for multiple wallets:

```sh
0x1234567890abcdef1234567890abcdef12345678
0xabcdef1234567890abcdef1234567890abcdef12
```

### 4. (Optional) Modify settings in `bot.js`:

- `MAX_QUESTIONS_PER_DAY = 30` (Adjust daily question limit per wallet)
- `MESSAGE_DELAY = 5 * 60 * 1000` (Change delay between each question)

## 🚀 Usage

Run the bot:

```sh
npm run start
```

The bot will prompt you to:

1. **Choose connection mode** (Direct/Proxy)
2. **Choose wallet input mode** (Manual/File)
3. **Enter wallet address** (if manual mode)

## ⚙️ Configuration Options

- **Rate Limiting:** Prevents exceeding limits
- **Agents:** Modify available AI agents
- **Interval Between Cycles:** Change delay between interaction cycles

## 📢 Support

Join our Telegram channel for updates and support:

👉 [https://t.me/HAMAD_ALPHA](https://t.me/HAMAD_ALPHA)

## ⚠️ Disclaimer

This bot is for **educational purposes only**. Use at your own risk and ensure compliance with Kite AI's terms of service.

## 📜 License

MIT License - feel free to use and modify for your own purposes.

