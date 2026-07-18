# Siribraheem Token on Arc Testnet

A simple ERC-20 token called **Siribraheem Token (ST)** deployed on **Circle's Arc blockchain** using Remix IDE.

## Contract Details

| Item                  | Value                                      |
|-----------------------|--------------------------------------------|
| **Token Name**        | Siribraheem Token                          |
| **Symbol**            | ST                                         |
| **Decimals**          | 18                                         |
| **Total Supply**      | 1,000,000 ST (minted to deployer)          |
| **Contract Address**  | `0xD0cE4a929A2C20A28A6DB3009aD47A31BBEf9e41`                |
| **Network**           | Arc Testnet                                |
| **Explorer**          | [View on Arcscan](https://testnet.arcscan.app/address/0xYourContractAddressHere) |
| **Deployment Tool**   | Remix IDE                                  |
| **Deployment Date**   | July 18, 2026                              |

---

## Overview

This project is a basic ERC-20 token named **Siribraheem Token (ST)** deployed on **Arc**, a Layer-1 blockchain built by **Circle** (the company behind USDC).

The goal of this project was to:
- Deploy a real working token on Arc Testnet
- Learn how to build and deploy smart contracts on Circle’s blockchain
- Document the full process clearly for learning and sharing

---

## How I Built This Contract

### Tools Used
- **Remix IDE** (browser-based Solidity development environment)
- **MetaMask** wallet connected to Arc Testnet
- OpenZeppelin’s audited ERC-20 standard

### Step-by-Step Deployment Process

1. Added **Arc Testnet** manually to MetaMask with these details:
   - RPC URL: `https://rpc.testnet.arc.network`
   - Chain ID: `5042002`
   - Currency Symbol: `USDC`

2. Created a new Solidity file in Remix called `SiribraheemToken.sol`

3. Wrote a clean ERC-20 contract that mints **1,000,000 ST** tokens to the deployer at the time of deployment.

4. Compiled the contract using Solidity version `^0.8.20`

5. Changed the environment in Remix to **Injected Provider - MetaMask**

6. Deployed the contract directly on **Arc Testnet**

7. The contract was successfully verified on Sourcify

---

## How Siribraheem Token (ST) Works

**Siribraheem Token** is a standard **ERC-20** token with the following features:

- **Name**: Siribraheem Token
- **Symbol**: ST
- **Total Supply**: 1,000,000 tokens (all minted during deployment)
- **Minting**: Tokens were only minted once at deployment to the contract owner
- **Transfers**: Fully transferable between any wallets
- **Standard Functions**: `transfer()`, `approve()`, `transferFrom()`, `balanceOf()`, `allowance()`, etc.

Because it uses OpenZeppelin’s secure and audited ERC-20 implementation, it follows best practices for security and compatibility with wallets and dApps.

---

## Deep Dive: What is Arc and Circle?

### What is Circle?
Circle is a major fintech company best known for creating **USDC**, one of the most widely used and regulated stablecoins in the world. Their mission is to make digital dollars and on-chain finance accessible, fast, and compliant.

### What is Arc?
**Arc** is Circle’s own **Layer-1 blockchain**, officially launched in late 2025. It is designed as an “Economic Operating System” built specifically for stablecoins, payments, and real-world financial applications.

#### Key Highlights of Arc:
- **USDC as Native Gas Token**: You pay transaction fees in USDC instead of a volatile cryptocurrency. This makes fees predictable and stable.
- **Extremely Fast**: Sub-second finality with very high throughput.
- **EVM Compatible**: You can deploy normal Solidity smart contracts (like this one).
- **Finance-Focused**: Built with strong support for tokenization, payments, RWAs, and future agentic economies.
- **Native Integrations**: Comes with Circle’s tools like CCTP, compliance features, and account abstraction out of the box.

Arc is currently running on **Public Testnet**. Mainnet is expected later in 2026.

---

## Why Deploy on Arc?

- Predictable fees paid in USDC
- Strong backing from Circle
- Growing ecosystem for financial applications
- Great learning environment for modern blockchain development
- Excellent compatibility with existing Ethereum tooling

---

## How to Use Siribraheem Token (ST)

### 1. Add the Token to MetaMask
- Go to **Add Token** in MetaMask
- Paste the contract address: `0xD0cE4a929A2C20A28A6DB3009aD47A31BBEf9e41`
- Symbol: `ST`
- Decimals: `18`

### 2. View the Contract on Explorer
[Click here to view Siribraheem Token on Arc Testnet Explorer](https://testnet.arcscan.app/address/0xYourContractAddressHere)

### 3. Interact with the Token
You can:
- Send and receive ST tokens
- Check your balance
- Approve other contracts to spend your tokens

All standard ERC-20 functions are available and working.

---

## Future Improvements

Possible next steps for this token:
- Add burning functionality
- Add pausable feature
- Implement role-based access control (Ownable)
- Deploy on Arc Mainnet when it launches
- Build a simple frontend dApp
- Explore Circle’s App Kit and other developer tools

---

## Resources & Links

- **Arc Official Documentation**: [https://docs.arc.io](https://docs.arc.io)
- **Circle Developer Console**: [https://console.circle.com](https://console.circle.com)
- **Arc Testnet Explorer (Blockscout)**: [https://testnet.arcscan.app](https://testnet.arcscan.app)
- **Remix IDE**: [https://remix.ethereum.org](https://remix.ethereum.org)
- **OpenZeppelin Contracts**: [https://docs.openzeppelin.com/contracts](https://docs.openzeppelin.com/contracts)

---

## License

This project is open source under the **MIT License**.

---

**Built on Arc Testnet using Remix IDE**  
**Siribraheem Token (ST)**
