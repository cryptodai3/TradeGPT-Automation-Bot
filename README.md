# 🚀 TradeGPT Automation Bot

An automated bot for interacting with **TradeGPT Finance** on the **0G Testnet** — perform swaps, simulate chat, and **earn airdrop points effortlessly**.

> 🧠 Built for the Web3 farming fam by [cryptodai3](https://t.me/cryptodai3)

---

## ✨ Key Features

* 🔀 **Auto Token Swaps** – USDT ➜ LOP (via Uniswap Router)
* 💬 **Chat Simulation** – Random prompts to mimic human interaction
* 👛 **Multi-Wallet Support** – Rotate wallets easily from `.env`
* 📈 **Points Tracking** – See how much you’re farming live
* 🛡️ **Secure & Testnet-only** – Perfect for safe experimentation

---

## ⚙️ Prerequisites

Before you start, make sure you have:

* ✅ **Node.js v18+**
* ✅ **npm** or **yarn**
* ✅ **0G Testnet** tokens:

  * `USDT` and `OG` (gas)
* ✅ **Private keys** stored in `.env`

---

## 🧪 Quick Setup (5 Steps)

### 1️⃣ Clone the repo

```bash
git clone https://github.com/cryptodai3/TradeGPT-Automation-Bot.git
```
```bash
cd TradeGPT-Automation-Bot
```

### 2️⃣ Install dependencies

```bash
npm install
# or
yarn install
```

### 3️⃣ Setup your wallets

Create a `.env` file based on `.env.example`:

```ini
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=your_optional_key_here
# Add more if needed
```

### 4️⃣ Confirm RPC and Tokens (0G Testnet default)
The bot comes with default settings for the 0G Testnet:
```js
const networkConfig = {
  rpc: 'https://evmrpc-testnet.0g.ai/',
  chainId: 16601,
  symbol: 'OG',
  explorer: 'https://chainscan-galileo.0g.ai/',
};
```

* USDT: `0xe6c489B6D3eecA451D60cfda4782e9E727490477`
* LOP: `0x8b1b701966cfdd5021014bc9c18402b38091b7a8`
* Router: `0xDCd7d05640Be92EC91ceb1c9eA18e88aFf3a6900`

### 5️⃣ Run the bot

```bash
node index.js
```

---

## 🤖 What It Does (Step by Step)

1. 💼 Shows wallet balances and point stats
2. 💬 Prompts for how many chat replies per wallet
3. 🗨️ Simulates human-like chat with TradeGPT
4. 🔄 Randomly swaps USDT ➜ LOP
5. 📊 Displays your updated points

---

## 🎨 Want to Customize?

* 🧠 `getRandomPrompt()` – Add your own chat messages
* 🔧 `networkConfig` – Switch RPC or explorer
* 💸 Swap settings – Control token amounts and frequency

---

## 🔒 Safety First

⚠️ **Security Tips**:

* Never reuse real wallets — testnet only!
* Never expose your private keys
* Review code before running
* Use a burner wallet with test tokens only

---

## 💬 Got Questions?

* Found a bug? Got an idea?
  👉 [Open an issue](https://github.com/cryptodai3/TradeGPT-Automation-Bot/issues) or [DM cryptodai3](https://t.me/cryptodai3)

---

## 🙌 Support This Bot

If this saved you time or boosted your airdrop game:

* ⭐ Star the repo
* 🔁 Share with your farming fam
* 💡 Suggest improvements

---

## ⚠️ Disclaimer

This tool is **strictly for testnet** use.
No guarantees. No liability. No 🚀 unless you DYOR.

---

## 📄 License

MIT — use freely, contribute wisely. 🙏

---
