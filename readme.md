# 🚀 Wall-et (ITBA Hackathon MVP)

![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Web3](https://img.shields.io/badge/Web3-Smart_Contracts-8A2BE2?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-Client%2FServer-blue?style=flat-square)

**Wall-et** is a decentralized Fintech MVP developed during the ITBA Hackathon. It serves as a secure onboarding platform to introduce financial literacy and crypto-economics to minors through a gamified, parent-controlled ecosystem.

## ⚙️ Tech Stack & Architecture

This repository is split into a modern micro-architecture:
* **`/CLIENT`**: The frontend user interface for both parent dashboards and child accounts.
* **`/SERVER`**: The backend infrastructure handling off-chain logic, user state, and API routing.
* **`/WEB-3`**: The blockchain layer containing the smart contracts and terminal deployment scripts.

## 🔐 Core Features

* **Multi-Signature Security (Multisig):** Implemented smart contracts requiring parent authorization for outbound transactions, creating a secure sandbox for crypto onboarding.
* **Dual-User Ecosystem:** Built distinct state flows for Parents (oversight, goal setting, transaction approval) and Children (saving, gamified learning).
* **Blockchain Interaction:** Configured Web3 integrations to allow manual smart contract deployment and transaction execution via the terminal.

## 🛠️ Local Deployment

To run this MVP locally, each environment must be initialized separately:

1. **Start the Backend:** Navigate to the `/SERVER` directory, install dependencies, and run the local server.
2. **Start the Frontend:** Navigate to the `/CLIENT` directory, install dependencies, and initialize the web app.
3. **Web3 Operations:** Refer to the specific README inside the `/WEB-3` folder to compile and test the smart contracts via terminal.
