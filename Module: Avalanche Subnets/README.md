# DeFi Empire: DeFi Kingdom Clone on Avalanche

## Overview

Welcome to DeFi Empire, a thrilling blockchain-based gaming experience where players can collect, build, and battle with their digital assets, earning rewards through various game activities. In this project, we have created a DeFi Kingdom clone on the Avalanche network, combining decentralized finance and gaming into an immersive universe.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Steps](#project-steps)
- [Smart Contracts](#smart-contracts)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following tools and resources:

- Unix computer (MacOS or Linux)
- Solidity programming language knowledge
- Remix online IDE
- Metamask wallet extension
- Web browser

## Project Steps

Follow these steps to create your DeFi Kingdom clone on Avalanche:

1. **Set up your EVM subnet:** Follow the provided guide and Avalanche documentation to create a custom EVM subnet on the Avalanche network. This enables low-fee deployment of your smart contracts and the creation of a custom token.

2. **Define your native currency:** Establish your own native currency, which serves as the in-game currency for your DeFi Kingdom clone. This currency facilitates transactions, rewards, and various in-game activities.

3. **Connect to Metamask:** Use the provided guide to connect your EVM Subnet to Metamask. Ensure your custom EVM subnet is selected as the network in Metamask.

4. **Deploy basic building blocks:** Leverage Solidity and Remix to deploy foundational smart contracts for your game. These contracts define activities like battling, exploring, and trading. Example contracts provided in the guide:

   - [ERC20 Token Contract](contracts/ERC20.sol)
   - [Vault Contract](contracts/Vault.sol)

5. **Test your application:** Utilize Remix to interact with your deployed smart contracts. Deploy tokens, liquidity pools, and other components critical to your DeFi Kingdom clone. Test functionalities such as battling, exploring, and trading within your game.

## Smart Contracts

We have deployed two foundational smart contracts for DeFi Empire:

1. **ERC20 Token Contract:** This contract implements a standard ERC20 token with functionalities for transfers, allowances, minting, and burning. Players can use this token as an in-game currency.

   - [ERC20.sol](contracts/ERC20.sol)

2. **Vault Contract:** The Vault contract enables users to deposit and withdraw their tokens while maintaining the total supply and individual balances. This contract serves as the basis for managing liquidity within the game.

   - [Vault.sol](contracts/Vault.sol)

## Usage

To start your DeFi Kingdom adventure, follow these steps:

1. Set up your EVM subnet using the provided guide and Avalanche documentation.

2. Define your native currency within the game.

3. Connect your EVM Subnet to Metamask as outlined in the guide.

4. Deploy the foundational smart contracts using Remix.

5. Test your DeFi Kingdom clone by interacting with the deployed smart contracts through Remix.

## Contributors

This project was created by [MetaCrafter Sirilux](https://twitter.com/AadityaChandan1).

## License

This project is licensed under the [MIT License](LICENSE).

