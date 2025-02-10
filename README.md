# gokite-ai

## Kite AI Auto-Bot

An automated interaction bot for the Kite AI platform with multi-wallet and proxy support.

## Register

- [Sign up here](https://testnet.gokite.ai?r=nmtN7225)

## 🌟 Features

- Multiple wallet support (manual input or file-based)
- Proxy support (HTTP/HTTPS/SOCKS)
- Rate limiting and retry mechanisms
- Multiple AI agents interaction
- Automatic question selection
- Usage reporting
- Graceful error handling
- **Automated messaging with a delay of 5 minutes per message**
- **Each wallet can send a maximum of 30 messages per 24 hours**

## 👌 Prerequisites

- Node.js (v16 or higher)
- npm (Node Package Manager)

## 🧐 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hamad0786/gokite-ai
   ```
   ```bash
   cd gokite-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 📝 Configuration

1. Create a `questions.json` file with your questions:
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

2. (Optional) Create a `proxies.txt` file for proxy support:
   ```
   http://user:pass@host:port
   socks5://user:pass@host:port
   ```

3. Create a `wallets.txt` file for multiple wallets:
   ```bash
   nano wallets.txt
   ```
   Add wallet addresses in the file:
   ```
   0x1234567890abcdef1234567890abcdef12345678
   0xabcdef1234567890abcdef1234567890abcdef12
   ```

## 🚀 Usage

Run the bot:
```bash
npm run start
```

The bot will prompt you to:
1. Choose connection mode (Direct/Proxy)
2. Choose wallet input mode (Manual/File)
3. Enter wallet address (if manual mode)

## ⚙️ Configuration Options

You can modify the following settings in `index.js`:

- `rateLimitConfig`: Adjust rate limiting parameters
- `agents`: Modify available AI agents
- `intervalBetweenCycles`: Change delay between interaction cycles
- **Message delay is set to 5 minutes per message**
- **Each wallet can send a maximum of 30 messages per 24 hours**

## 📢 Support

Join our Telegram channel for updates and support:
[HAMAD_ALPHA Telegram](https://t.me/HAMAD_ALPHA)

## ⚠️ Disclaimer

This bot is for educational purposes only. Use at your own risk and ensure compliance with Kite AI's terms of service.

## 🐟 License

MIT License - feel free to use and modify for your own purposes.

