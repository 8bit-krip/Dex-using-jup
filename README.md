# 🚀 Jupiter SOL → USDC Swap Script (Node.js)

This script uses [Jupiter Aggregator](https://www.jup.ag/) APIs to swap **SOL** to **USDC** on the Solana blockchain using a backend script in Node.js.

## 🧠 What This Script Does

- Connects to the Solana **mainnet**
- Uses **Jupiter Quote API** to get the best swap rate for SOL → USDC
- Calls the **Swap API** to get the encoded transaction
- Signs and sends the transaction using your private key
- Prints the **transaction ID** and **Solscan link** after confirmation

---

## 📦 Tech Stack

- [Solana Web3.js](https://solana-labs.github.io/solana-web3.js/)
- [Jupiter Aggregator API](https://station.jup.ag/docs)
- [Anchor Wallet](https://project-serum.github.io/anchor/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Axios](https://axios-http.com/)

---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/week-9-swap-contract.git
cd Dex-using-jup
