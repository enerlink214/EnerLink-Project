# ⚡ EnerLink

> Decentralized Smart ISP Switching + Unified Payment Gateway  
> Built on Solana. Designed for Africa. Powered by Web3.

---

## 🌍 Overview

EnerLink is a decentralized, smart-switching internet service layer that automatically connects users to the best-performing ISP (MTN or Airtel) based on real-time signal strength — without SIM swaps.

With one blockchain-based payment, users unlock seamless access to multiple ISPs through an intelligent, censorship-resistant platform hosted on IPFS and accessed via ENS.

---

## 🎯 Bounty Track Alignment

- ✅ **Nouns** – ENS + IPFS Frontends  
- ✅ **Protocol Labs** – Decentralized Hosting & Fresh Code  
- ✅ **Wildcard** – Secure, Sovereign Systems

---

## 🧠 Key Features

### 🔀 Smart ISP Switching Engine  
- Monitors signal strength in real time  
- Automatically switches to stronger ISP (MTN or Airtel)  
- Powered by backend logic + automation bots

### 💳 Unified Blockchain Payment  
- One-time crypto payment covers multiple ISPs  
- Pay-per-KB logic tracked onchain  
- Smart contracts built with Anchor on **Solana**

### 🔐 Decentralized UI  
- Hosted on IPFS via Web3.Storage  
- Accessible via ENS: `enerlinklab.eth`  
- No central servers or domains

---

## 🔧 Tech Stack

| Layer            | Stack / Tools               |
|------------------|-----------------------------|
| Smart Contracts  | Rust, Solana, Anchor        |
| Frontend         | React, Next.js, Tailwind    |
| Backend          | NestJS (Node.js), REST APIs |
| Hosting          | IPFS via web3.storage       |
| Domain           | ENS: `enerlinklab.eth`      |
| Wallet           | MetaMask, Ethers.js         |
| Design           | Figma (Hi-Fi, Lo-Fi)        |

---

## 🛠 Architecture Overview

```plaintext
[User Wallet]
     ↓
[ENS: enerlinklab.eth]
     ↓
[IPFS Frontend] ←→ [NestJS Backend] ←→ [MTN / Airtel APIs]
                          ↓
                [Solana Smart Contracts]