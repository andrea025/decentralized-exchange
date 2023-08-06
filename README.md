# Decentralized Exchange (DEX)

This repository contains the code for a Decentralized Exchange (DEX), which is integral part of the DeFi ecosystem. The project is implemented using Solidity and the Hardhat framework, and comes with a React frontend. You can run it locally to understand how decentralized finance (DeFi) works.

## Overview

The Decentralized Exchange enables users to trade tokens without relying on an intermediary, thus enhancing privacy, security, and control. This project provides a hands-on way to explore how decentralized technologies work in the context of digital assets trading.

## Features

- **Smart Contracts**: Implemented using Solidity and deployed using Hardhat.
- **Frontend**: A web interface built with React to interact with the deployed contracts.
- **Local Environment**: Ability to run and test the exchange locally.

## Getting Started

### Prerequisites

- Node.js
- Hardhat
- MetaMask

### Commands

```shell
npm install
npx hardhat compile
npx hardhat test
npx hardhat node
npx hardhat run --network localhost ./scripts/1_deploy.js
npx hardhat run --network localhost ./scripts/2_seed-exchange.js
npm run start
```
