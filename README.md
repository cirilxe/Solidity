# MyToken - Simple Token Contract

This is a simple Ethereum smart contract written in Solidity for creating and managing a custom token called `META` (MTA). The contract allows you to mint (create) and burn (destroy) tokens for a specified Ethereum address. This README provides an overview of the contract and instructions for its usage.

## Table of Contents

1. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
2. [Usage](#usage)
    - [Minting Tokens](#minting-tokens)
    - [Burning Tokens](#burning-tokens)

## Getting Started

### Prerequisites

Before you can use this contract, make sure you have the following prerequisites:

- Ethereum Wallet or MetaMask: You need an Ethereum wallet or MetaMask extension to interact with this contract on the Ethereum blockchain.
- Ether: You'll need a small amount of Ether to cover transaction fees when interacting with the contract.

### Installation

There is no installation required for the contract itself. You can interact with it directly on the Ethereum blockchain using your preferred Ethereum wallet or development environment.

## Usage

### Minting Tokens

The `mint` function allows you to create new tokens and assign them to a specified Ethereum address. To mint tokens, follow these steps:

1. Connect your Ethereum wallet or MetaMask to the Ethereum network.
2. Navigate to the `MyToken` contract address on your Ethereum wallet.
3. Access the `mint` function and provide the following parameters:
   - `_address`: The Ethereum address to which you want to mint tokens.
   - `_value`: The number of tokens you want to create and assign.

### Burning Tokens

The `burn` function allows you to destroy tokens held by a specified Ethereum address. This is irreversible, so be careful when using this function. To burn tokens, follow these steps:

1. Connect your Ethereum wallet or MetaMask to the Ethereum network.
2. Navigate to the `MyToken` contract address on your Ethereum wallet.
3. Access the `burn` function and provide the following parameters:
   - `_address`: The Ethereum address from which you want to burn tokens.
   - `_value`: The number of tokens you want to destroy.
