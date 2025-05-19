# ⚙️ Blockchain Consensus Mechanisms

Okay... so what keeps a blockchain honest? How do all the nodes agree on the current state of the chain?

That's where **consensus mechanisms** come in.

---

## 🔨 1. Proof of Work (PoW)

Used by: **Bitcoin**, early **Ethereum**

This is the OG method. Miners compete to solve a **hard math puzzle** (hashing). Whoever wins, gets to add the next block and earns crypto rewards.

### ⚡ Quick Points:
- Energy-heavy 😵‍💫
- Very secure but slow
- Needs **computational power**
- Encourages decentralization, but not environment-friendly

> Think: brute force + fastest wins.

---

## 💰 2. Proof of Stake (PoS)

Used by: **Ethereum 2.0**, **Polygon**, **BNB Chain**, **Avalanche**

Here, instead of mining, validators **lock up coins (stake)** to win the chance to create the next block.

### ⚡ Quick Points:
- Energy-efficient ⚡
- Richer = higher chance to validate
- Can lose your stake for bad behavior (called **slashing**)

> Think: wealthy + trustworthy = validator

---

## 🕒 3. Proof of History (PoH)

Used by: **Solana**

Solana uses time itself as part of consensus. It uses cryptographic timestamps to prove that events happened in a certain order — super fast.

### ⚡ Quick Points:
- Built for **speed**
- Adds **timestamps** to every transaction
- Works with **Tower BFT** (Solana’s own flavor of PoS)

> Think: "time-tracked" blockchain

---

## 📦 4. Proof of Capacity (PoC)

Used by: **Burstcoin**, **Chia**

Instead of CPU/GPU power or coins, PoC uses **hard drive space** to plot and store solutions to the mining problem.

### ⚡ Quick Points:
- Eco-friendly 🌱
- Uses **storage** instead of power
- Good for home miners

> Think: “I got more storage = I win”

---

## 📡 Other Mechanisms (Just FYI)

- **DPoS (Delegated Proof of Stake)** — used in EOS, TRON (vote for validators)
- **PBFT (Practical Byzantine Fault Tolerance)** — used in private chains
- **PoA (Proof of Authority)** — used in enterprise chains (validators are known)

---

## 🤔 Why Should I Care?

Choosing the right consensus mechanism affects:
- 🔒 Security
- ⚡ Speed
- 🌍 Decentralization
- ♻️ Energy usage

Each blockchain picks what fits best for their goal. For example:
- Bitcoin wants max security → uses PoW
- Solana wants speed → uses PoH + PoS
- Ethereum moved to PoS to go green 🌱

---

📘 _Next up: Smart Contracts & DApps Basics →_

