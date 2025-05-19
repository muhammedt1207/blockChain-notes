# 🚀 Solana Token & dApp Learning Notes

Welcome to my personal learning repository focused on building tokens and decentralized applications (dApps) on the **Solana blockchain**.

This repo documents everything I'm learning — from the basics of Solana to writing and deploying smart contracts, creating tokens, and building frontend dApps that interact with the blockchain.

---

## 📚 Table of Contents

- [🔰 Introduction](#-introduction)
- [🌐 What is a dApp?](#-what-is-a-dapp)
- [⚙️ Solana Environment Setup](#️-solana-environment-setup)
- [📜 Writing Smart Contracts (Programs)](#-writing-smart-contracts-programs)
- [💸 Creating a Solana Token](#-creating-a-solana-token)
- [🖥️ Building a Frontend dApp](#️-building-a-frontend-dapp)
- [📦 Tools & Libraries Used](#-tools--libraries-used)
- [📎 Resources](#-resources)

---

## 🔰 Introduction

Solana is a high-performance blockchain supporting fast transactions and low fees. It's ideal for building scalable decentralized applications (dApps) and DeFi platforms.

In this project, I document:
- How Solana works under the hood.
- Steps to create your own token on Solana.
- How to build and deploy smart contracts (called "Programs" in Solana).
- Building a full-stack dApp that interacts with those programs.

---

## 🌐 What is a dApp?

A **dApp (Decentralized Application)** is:
- An application that runs on a blockchain network.
- Backend logic lives in smart contracts.
- Frontend can be traditional (React/Next.js), but it communicates with the blockchain.

> In Solana, smart contracts are called **Programs**, written using **Rust** or **Anchor framework**.

---

## ⚙️ Solana Environment Setup

To get started with Solana development:

```bash
# Install Solana CLI
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"

# Check version
solana --version

# Install Anchor framework (recommended)
npm install -g @coral-xyz/anchor-cli
