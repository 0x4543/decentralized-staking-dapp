# 🔏 Decentralized Staking dApp

A decentralized Ethereum staking application built as part of the **SpeedRunEthereum Challenge #2** — “Decentralized Staking App”.

## 🌐 Live Demo

* **Frontend (Vercel):** [staker-ui](https://nextjs-os19pn2mf-dormins-projects.vercel.app/staker-ui)
* **Smart Contract (Sepolia):** [0x89A7FBC572c734b48A1fbf79c7F4ba7DB73A6Fea](https://sepolia.etherscan.io/address/0x89A7FBC572c734b48A1fbf79c7F4ba7DB73A6Fea)

## 🧬 About

This project demonstrates a minimal Ethereum dApp that allows users to:

* Stake ETH into a smart contract before a deadline
* Trigger automatic staking completion via `execute()`
* Withdraw funds if the threshold is not met
* Track on-chain events and balances via Next.js frontend

## 🧱 Stack

* **Solidity / Hardhat** — Smart contract development and deployment
* **Next.js / React / Tailwind** — Frontend
* **Viem / Wagmi / RainbowKit** — Web3 integration
* **Alchemy / Etherscan** — RPC & verification
* **Vercel** — Deployment

## ⚙️ Local Setup

```bash
# Install dependencies
yarn install

# Start local Hardhat chain
yarn chain

# Deploy contracts
yarn deploy

# Run frontend
yarn start
```

## 🗾 License

MIT
