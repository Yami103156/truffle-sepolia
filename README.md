# 🧠 Truffle Sepolia Smart Contracts Deployment

This project demonstrates how to write, compile, and deploy Ethereum smart contracts using the [Truffle Framework](https://trufflesuite.com) and deploy them to the **Sepolia testnet** using **Alchemy** and **HDWalletProvider**.

---

## 🚀 Features

- ✍️ Solidity smart contracts (`SimpleStorage.sol`, `ABC.sol`)
- 🧪 Compiled with Solidity 0.5.1
- 🌐 Deployed to Sepolia Testnet
- 🔐 Secrets managed via `.env`
- 📦 Powered by Truffle, Alchemy, MetaMask

---

## 🛠️ Project Structure

```bash
├── contracts/           # Solidity contracts
│   ├── SimpleStorage.sol
│   └── ABC.sol
├── migrations/          # Truffle migration scripts
│   ├── 1_simpleStorage.js
│   └── 2_abc.js
├── test/                # (optional) Mocha/Chai test files
├── build/               # Auto-generated compiled contract ABIs
├── .env                 # Your secrets (NOT committed to Git)
├── truffle-config.js    # Network and compiler config




🧪 Requirements
Node.js v18.x (recommended)
Truffle v5.x
MetaMask wallet
Alchemy API key (or Infura alternative)
Sepolia ETH (via faucet)
└── package.json

📄 License
MIT License

🙌 Acknowledgements
Truffle Suite
Alchemy
MetaMask
