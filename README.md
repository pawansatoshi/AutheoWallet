# Autheo Wallet
A lightweight, serverless EVM wallet engineered for the Autheo Testnet, featuring real-time ledger tracking, dynamic QR codes, and voice-confirmed transactions

## Project Overview
A lightweight, professional EVM-compatible wallet interface built exclusively for the Autheo Testnet. Engineered for mobile browsers, this application operates on raw HTML, CSS, and JavaScript, ensuring instant deployment and zero-build overhead on serverless platforms like Vercel.

## Important Links & Network Configuration
To interact with the application, users must configure their web3 extensions (MetaMask, OKX Wallet) with the following parameters:

* **Network Name:** Autheo Testnet
* **Chain ID:** 785 (Hex: 0x311)
* **Currency Symbol:** THEO
* **RPC URL:** https://testnet-rpc1.autheo.com
* **Block Explorer:** https://testnet-explorer.autheo.com
* **Faucet:** https://testnet-faucet.autheo.com/

## Core Features
* **Universal Provider Support:** Seamlessly detects and connects to injected EVM wallets.
* **Real-Time Synchronization:** Auto-fetches balance updates and listens for network/account changes.
* **Live Ledger History:** Captures the transaction hash, calculates the exact time taken from broadcast to confirmation, and displays the exact gas fee charged.
* **Voice Confirmation:** Utilizes the Web Speech API to provide an auditory announcement upon successful transaction mining.
* **Dynamic Barcode:** Automatically generates a unique QR code for the connected public address to facilitate quick receiving.

## Setup & Deployment (Mobile Workflow)
This project is optimized to be built and deployed entirely from an Android mobile browser using GitHub and Vercel.

1. **Repository Setup:** Create a new GitHub repository.
2. **File Addition:** Add the provided `index.html` file to the root of the repository.
3. **Brand Asset:** Upload your official `logo.png` to the exact same root directory.
4. **Vercel Integration:** * Open the Vercel dashboard and select "Add New Project."
   * Import this GitHub repository.
   * Ensure the Framework Preset is left as default (Other/None).
   * Deploy the application.
