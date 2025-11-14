# 🔏 Decentralized Staking dApp

A decentralized Ethereum staking application built as part of the [**SpeedRunEthereum Challenge #2 — Decentralized Staking App**](https://speedrunethereum.com/challenge/decentralized-staking).

## 🌐 Live Demo

- **Frontend (Vercel):** [staker-ui](https://nextjs-iwh04s6kw-dormins-projects.vercel.app/staker-ui)
- **Smart Contract (Sepolia):** [0xD512726A446aDE2c56F8AD0da5412E801F03ebe1](https://sepolia.etherscan.io/address/0xD512726A446aDE2c56F8AD0da5412E801F03ebe1)

## 🧬 About

This project demonstrates a minimal Ethereum dApp that allows users to:

- Stake ETH into a smart contract before a deadline
- Trigger automatic staking completion via `execute()`
- Withdraw funds if the threshold is not met
- Track on-chain events and balances via Next.js frontend

## 🧱 Stack

- **Solidity / Hardhat** — Smart contract development and deployment
- **Next.js / React / Tailwind** — Frontend
- **viem / wagmi / RainbowKit** — Web3 integration
- **Alchemy / Etherscan** — RPC & verification
- **Vercel** — Deployment

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

[MIT](LICENSE)
