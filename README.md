# Smart Contract Development and Deployment using Scaffold-ETH 2

## Overview

This project is developed using Scaffold-ETH 2 a modern full-stack Ethereum development environment that helps in building, deploying, and testing decentralized applications. It provides an organized structure for writing Solidity smart contracts, deploying them on a local blockchain, and connecting them with a frontend interface for interaction and debugging.

The project is useful for learning blockchain development as well as creating Ethereum-based applications in a structured and practical way. It combines smart contract development with frontend integration so that users can deploy contracts, connect wallets, and test contract functions from a browser.

## Technologies Used

The project is built using the following technologies:

- **Next.js** for frontend development
- **Hardhat** for compiling, testing, and deploying smart contracts
- **Solidity** for writing Ethereum smart contracts
- **TypeScript** for better code structure and type safety
- **RainbowKit** for wallet connection
- **Wagmi** for smart contract interaction in React
- **Viem** for Ethereum utilities and client handling

## Features

This project provides the following features:

- Development of Ethereum smart contracts using Solidity
- Local blockchain setup for testing and deployment
- Deployment of contracts using Hardhat
- Wallet integration using MetaMask or other supported wallets
- Debug Contracts page for testing deployed smart contracts
- Frontend and blockchain connectivity in a single environment
- Easy modification of contract, deployment, and UI files during development

## Requirements

Before running the project, make sure the following software is installed on your system:

- **Node.js** version 18.17 or above
- **Yarn**
- **Git**

## Project Structure

The project follows a structured folder layout:

- `packages/hardhat/contracts` – contains Solidity smart contracts
- `packages/hardhat/deploy` – contains deployment scripts
- `packages/hardhat/hardhat.config.ts` – Hardhat configuration file
- `packages/nextjs/app/page.tsx` – frontend homepage
- `packages/nextjs/app/debug/page.tsx` – Debug Contracts page
- `packages/nextjs/scaffold.config.ts` – frontend configuration settings

## How to Run the Project

To run the project successfully, follow the steps below.

### Step 1: Install Dependencies

Open the terminal in the project folder and run:

```bash
yarn install
```
### Step 2: Start the Local Blockchain
bash
yarn chain
This starts a local Ethereum blockchain using Hardhat. It creates a development network on your system where contracts can be deployed and tested safely.
### Deploy the Smart Contract
Open a second terminal and run:
yarn deploy

This command compiles and deploys the smart contracts available in the packages/hardhat/contracts folder. The deployment scripts from the packages/hardhat/deploy folder are used during this process.

### Start the Frontend Application

Open a third terminal and run:
yarn start

### ### After this, open the browser and visit:

http://localhost:3000

The application frontend will load, and you can connect your wallet and access the Debug Contracts page.

### Purpose of the Project
The main purpose of this project is to provide a complete development environment for Ethereum smart contract applications. It helps developers understand how blockchain contracts are written, deployed, and connected to web interfaces. It is suitable for learning, experimentation, and building decentralized applications with a clear project structure.

### Using Scaffold-ETH 2

Using Scaffold-ETH 2 makes blockchain development easier because it already provides the required project setup for contract deployment, frontend interaction, and wallet support. Instead of creating everything from scratch, developers can focus on writing business logic and testing application behavior.

It is especially useful for beginners because it simplifies the connection between Solidity contracts and React-based frontend pages.

### Conclusion:

This project serves as a complete starter environment for blockchain application development using Ethereum. By using Scaffold-ETH 2, developers can write Solidity contracts, deploy them on a local network, connect wallets, and interact with them through a frontend application. The project is helpful for both educational purposes and practical decentralized application development.