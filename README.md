# 🚀 Algo-Intent: AI-Powered Algorand Wallet & Trading Assistant

![Built with Bolt.new](https://bolt.new/badge.svg)

**Algo-Intent** is a next-generation, AI-powered web app that lets you manage Algorand wallets, trade tokens, mint NFTs, and learn about blockchain—all through natural language chat. Built with [Bolt.new](https://bolt.new), it's your all-in-one assistant for the Algorand ecosystem.

---

## ✨ Features

- **AI Intent Parsing:** Use plain English to send ALGO, swap tokens, mint NFTs, and more.
- **Wallet Management:** Connect Pera, Defly, or Exodus wallets securely.
- **Send ALGO & NFTs:** Transfer assets, opt-in/out, and batch send with atomic groups.
- **NFT Minting:** Create NFTs with images or videos, stored on IPFS via Pinata.
- **Trading Operations:** Swap tokens, set limit/stop-loss orders, and check live prices.
- **Educational Chat:** Ask about Algorand, DeFi, trading, and blockchain concepts.
- **Network Switching:** Instantly toggle between TestNet and MainNet.
- **Modern UI:** Responsive, real-time chat with transaction status and wallet integration.
- **Security First:** All actions require wallet approval; no private keys or sensitive data stored.

---

## 🖼️ Demo

> **Live Demo:** [YOUR_PUBLIC_URL_HERE]  
> **Bolt.new Project:** [YOUR_BOLT_NEW_URL_HERE]  
> **Demo Video:** [YOUR_YOUTUBE_LINK_HERE]

---

## 🏆 Built for the Bolt.new Hackathon

- **Built with Bolt.new** ([see project](https://bolt.new/~/...))
- **Badge:** The app displays the official "Built with Bolt.new" badge.
- **Challenge/Bonus Prizes:** _[List any you're entering and how you qualify]_
- **Region:** _[Your region selection]_

---

## 💡 Example Commands

- `Send 2 algos to K54ZT...`
- `Create 10 nfts with name Universe and description "This image shows our milky way"`
- `Swap 50 USDC to ALGO`
- `Set stop-loss for 50 ALGO at $0.18`
- `What is Algorand?`
- `Create NFT named "Sunset" with description "Evening view"` _(attach an image!)_

---

## 🛠️ Getting Started

1. **Clone the repo:**
   ```bash
   git clone <repository-url>
   cd algointent/projects/algointent
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment:**
   Create a `.env` file:
   ```env
   VITE_ALGOD_SERVER=https://testnet-api.algonode.cloud
   VITE_ALGOD_PORT=443
   VITE_ALGOD_TOKEN=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
   VITE_PERPLEXITY_API_KEY=your_perplexity_api_key_here
   VITE_COINGECKO_API_KEY=your_coingecko_api_key_here
   VITE_PINATA_API_KEY=your_pinata_api_key_here
   VITE_PINATA_API_SECRET=your_pinata_api_secret_here
   ```

4. **Run locally:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173)

---

## 🗂️ Project Structure

```
src/
├── components/         # UI components (chat, wallet, etc.)
├── services/           # AI, trading, IPFS, transaction logic
├── utils/              # Network config, helpers
└── ...
```

---

## 🔒 Security

- **Client-side only:** No server-side storage of sensitive data.
- **Wallet integration:** Uses official Algorand wallet connectors.
- **Explicit approval:** All transactions require user confirmation.

---

## 🌐 Supported Networks

| Network | Status  | Explorer Link                          |
|---------|---------|----------------------------------------|
| Testnet | ✅ Live | https://testnet.explorer.perawallet.app|
| Mainnet | ⚠️ Beta | https://explorer.perawallet.app/       |

---

## 🛡️ Troubleshooting

- **Transaction failed?** Check the TxID in [Pera Explorer](https://testnet.explorer.perawallet.app).
- **NFT/ALGO not received?** Ensure opt-in and check wallet balance.
- **App doesn't understand?** Try rephrasing or use example commands.
- **File upload failed?** Check Pinata keys and file size (<1GB).
- **Trading not working?** Trading is simulated; real DEX integration is in progress.

---

## 🤝 Contributing

Pull requests, issues, and feature suggestions are welcome!

---

## 📜 License

MIT License — see [LICENSE](LICENSE)

---

## 🙋 FAQ

- **Can I use this on mainnet?** Yes, just update your `.env` and assets to a mainnet node.
- **Is my wallet safe?** Yes, private keys never leave your device.
- **How does the AI work?** It uses advanced intent parsing with deep Algorand knowledge.
- **What wallets are supported?** Pera, Defly, and Exodus.
- **Are trading features real?** Currently simulated; DEX integration coming soon.

---

**Built with ❤️ and [Bolt.new](https://bolt.new) for the Bolt Hackathon 2025!**

---

## 🏗️ Built With

<p align="center">
  <img src="./netlify.svg" alt="Netlify" height="48" style="margin-right: 24px;"/>
  <img src="./algorandimage.svg" alt="Algorand" height="48"/>
</p>
