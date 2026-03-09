# 🎬 Drishya – Decentralized Film Distribution Platform

Drishya is a **next-generation decentralized film distribution and rental platform** built on the **Ethereum Blockchain**.
It reshapes the relationship between filmmakers and their audience by **removing centralized intermediaries**, ensuring **fair monetization**, and offering a **censorship-resistant home** for creative work.

---

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Deployment: Vercel](https://img.shields.io/badge/Deployment-Vercel-black?logo=vercel)
![Meme Spotlight: Chainlink VRF](https://img.shields.io/badge/Meme%20Spotlight-Chainlink%20VRF-375BD2?logo=chainlink)

---

## 🌟 The Problem

The modern digital media landscape is dominated by centralized platforms that act as **powerful gatekeepers**.
This creates a severe **power imbalance** for independent creators:

- **💸 Extractive Fees** – Platforms often take **30–55%** of revenue with **opaque, delayed payments**.
- **🚫 Censorship & Loss of Control** – Arbitrary “community guidelines” can **deplatform** creators without recourse.
- **🛑 High Barriers to Entry** – Securing distribution deals is a **major hurdle** for many talented filmmakers.
- **⚠ Platform Risk** – Sudden changes in terms of service can **destroy a creator’s livelihood** overnight.

---

## ✨ The Drishya Solution

Drishya solves these problems by leveraging **Web3 technology** and the **Ethereum Blockchain**:

| Feature | Benefit |
|---------|---------|
| **🎥 Creator Sovereignty** | Immutable smart contracts remove Drishya as the intermediary. |
| **⚡ Fair & Instant Payments** | 90% of rental revenue paid instantly to creators’ wallets. |
| **🛡 Censorship Resistance** | Films stored on IPFS via specialized storage solutions – resilient & tamper-proof. |
| **🌍 Permissionless Access** | Anyone can upload films and monetize globally. |
| **🎁 Community Rewards** | Participate in the **Meme Spotlight** to win a 20% rental discount. |

---

## 🚀 Key Features

- **Dual-Portal Architecture**
  - 🎬 **Creator Portal** – Upload films, manage profiles, track on-chain earnings in real time.
  - 🍿 **Viewer Portal** – Discover, rent, and watch indie films with a **modern streaming experience**.

- **Web3-First Design**
  - Decentralized storage (IPFS + Pinata fallback)
  - Automated smart contract rental lifecycle
  - Wallet-based identity (MetaMask, RainbowKit)

- **New Feature: Meme Spotlight**
  - **User-Submitted Memes:** Viewers can upload relevant memes *free of cost* for community enjoyment.
  - **Random Selection:** The platform **admin** can trigger the **Spotlight of the Day** to randomly select a winning meme.
  - **Decentralized Randomness:** The selection process uses **Chainlink VRF (Verifiable Random Function)** for provably fair, tamper-proof randomness.
  - **Reward:** The creator of the selected meme wins a **20% discount** on their next film rental transaction.

- **Modern UI/UX**
  - Built with **Next.js**, **Tailwind CSS**, **Framer Motion**, **shadcn/ui**
  - Fully **responsive** and **mobile-friendly**

---

## 🛠 Tech Stack & Tools

**Frontend**
- Framework: `Next.js (React)`
- Styling: `Tailwind CSS`
- UI Components: `shadcn/ui`
- Animations: `Framer Motion`

**Web3 Integration**
- Blockchain: `Polkadot Hub`
- Wallet: `RainbowKit`
- Contract Interaction: `wagmi`, `viem`
- Randomness: `Chainlink VRF`

**Smart Contract**
- Language: `Solidity`
- Dev Environment: `Hardhat` / `Foundry`

**Storage**
- Primary: `IPFS (via specialized SDK/Gateway)`
- Fallback: `Pinata`

**Deployment**
- Platform: `Vercel`

---

## 🏁 Getting Started

### 📋 Prerequisites
- Node.js v18+
- `pnpm` / `npm` / `yarn`
- Web3 wallet (e.g., MetaMask)

### 📦 Installation
```bash
# Clone the repository
git clone [https://github.com/your-username/Drishya.git](https://github.com/your-username/Drishya.git)
cd Drishya

# Install dependencies
pnpm install
