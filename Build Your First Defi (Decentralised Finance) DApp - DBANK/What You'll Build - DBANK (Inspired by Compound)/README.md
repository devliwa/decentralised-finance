# 🚧 What You'll Build — DBANK (Inspired by Compound)

**Project:** DBANK — a simplified, educational decentralized lending & borrowing protocol inspired by Compound.
---
## Resources
- [Compound](https://app.compound.finance/?market=usdc-mainnet)
---
DBANK teaches core DeFi building blocks by guiding you to implement a minimal lending market where users can:
- **Deposit** an ERC-20 token to earn interest.
- **Borrow** against supplied collateral.
- **Repay** loans and **withdraw** collateral.
- View balances, supplied assets, and outstanding loans in a clean frontend.

This is **not** a production-ready protocol — it’s a learning project to understand how lending protocols, interest accrual, and smart-contract-backed workflows work.

---

## 🎯 Learning Objectives

By building DBANK you'll learn to:
- Write and test **Solidity smart contracts** for lending/borrowing logic.
- Implement **interest accrual** and basic collateralization checks.
- Use **Ethers.js / Web3.js** to interact with smart contracts.
- Build a **React** frontend that connects to MetaMask (or WalletConnect).
- Deploy to a **testnet** (e.g., Sepolia / Goerli / Polygon testnet) and verify contracts.
- Write unit and integration tests with **Hardhat** or **Truffle**.
- Understand security considerations and limitations of a simple lending protocol.

---

## 🧩 Core Features (Minimum Viable DBANK)

- `Supply`: Deposit ERC-20 tokens to the protocol and receive internal balance credit.
- `Borrow`: Request a loan denominated in the same (or another) ERC-20 token using supplied assets as collateral.
- `Repay`: Pay back borrowed amount + accrued interest.
- `Withdraw`: Remove supplied tokens if health factor is safe.
- `View`: Frontend pages to see supplied balance, borrowed balance, and interest rates.
- **Simple interest model** for learning (per-block or per-second accrual).

---

## 🛠️ Tech Stack

- **Smart Contracts:** Solidity (0.8.x)  
- **Dev Tools:** Hardhat (recommended) or Truffle  
- **Frontend:** React (Create React App / Vite / Next.js)  
- **Blockchain Interaction:** Ethers.js (preferred) or Web3.js  
- **Wallets:** MetaMask, WalletConnect  
- **Testing:** Hardhat + Mocha/Chai (or Truffle tests)  
- **Optional:** OpenZeppelin contracts (ERC20, SafeMath patterns if needed)

---

## 🧭 Architecture Overview
