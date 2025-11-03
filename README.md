# 🗳️ Decentralized Voting System

A blockchain-powered voting application built using **Solidity**, **Node.js**, and a **web frontend** — designed to create a transparent and tamper-resistant election platform.

---

## 🚀 Features

- Smart contract implementation in **Solidity** to manage:
  - Voter and candidate registration  
  - Secure voting  
  - Real-time result tallying  
- **Node.js** backend API for off-chain logic (user management, authentication).  
- **Frontend interface** for admins and voters with Web3.js or Ethers.js integration.  
- **Database layer** (in `Database_API/`) for storing non-sensitive data.  
- **Truffle** or compatible framework for contract deployment.  
- Secure configuration via `.env`.

---

## 📁 Project Structure/
|
├── contracts/ # Solidity smart contracts
├── migrations/ # Contract deployment scripts
├── Database_API/ # Node.js backend for off-chain data
├── public/ # Frontend static assets
├── src/ # Frontend source files
├── .vscode/ # VSCode workspace settings
├── index.js # Backend entry point
├── package.json # Dependencies & scripts
├── truffle-config.js # Truffle configuration
├── .env # Environment variables (ignored)
└── .gitignore # Files ignored by Git



---

## 🛠️ Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm or yarn
- Truffle Suite (or Hardhat)
- Local blockchain (e.g., Ganache) or access to a testnet
- MetaMask or similar wallet for Web3 interactions

### Installation

```bash
# Clone the repo
git clone https://github.com/yogesh032003/Decentralized_Voting_System.git
cd Decentralized_Voting_System

# Install dependencies
npm install
